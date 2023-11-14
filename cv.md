<image src="https://ltdfoto.ru/images/2023/11/14/small.jpg"></image>

## Full Name
Aidar Ibatullin      															

## Contact Information
- Location: Kazan, Tatarstan, Russia
- Phone: +7-937-15-15-15-3
- Email: a.ibatullin@gmail.com
- GitHub: [skySamurai](https://github.com/skysamurai)
- LinkedIn: [Aidar Ibatullin](https://www.linkedin.com/in/aidar-ibatullin-1b81611a6/)

## Brief Self-Introduction
I have been interested in computers since childhood. I love learning something new and strive to grow. My strengths: independence, calmness, quick decision making. I want my hobby to become my job and I am ready to make every effort for this.

## Skills
- HTML
- CSS/SASS
- JavaScript (Basic)
- Git
- С, С++

## Code examples
#### Description
Our football team has finished the championship.
Our team's match results are recorded in a collection of strings. Each match is represented by a string in the format "x:y", where x is our team's score and y is our opponents score.
For example: ["3:1", "2:2", "0:1", ...]
Points are awarded for each match as follows:
if x > y: 3 points (win)
if x < y: 0 points (loss)
if x = y: 1 point (tie)
We need to write a function that takes this collection and returns the number of points our team (x) got in the championship by the rules given above.


function points(games) {
  let points = 0;
  for (let i = 0; i < 10; i++){
    points += games[i].split("\:")[0] > games[i].split("\:")[1] ? 3 :
    games[i].split("\:")[0] == games[i].split("\:")[1] ? 1 : 0
  }
  return points;
}

## Work Experience
- Worked as an engineer at a plant for 9 years;
- 2 years as commercial director in a construction company;
- More than 5 years of freelancing work (one-page sites, simple sites for companies, various small tasks)

## Education
#### University: 
1. Ufa State Petroleum Technical University, specialty “Engineer”;
2. Bashkir Academy of Public Service and Management, specialty “Economist”

## English Language 
B1 – Intermediate