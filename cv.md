# Curriculum Vitae #
 
 
## Natalya Poida ##
 
 ![image](crop.jpg)
        
## my contacts ##       
 - Phone: +7 951 458 3977          
 - E-mail: nataly.poida@gmail.com
 - Telegram: https://t.me/natalypoida
 
## my projects ##
 - [Audiocall](https://audiocall.netlify.app/)           
 - [Movie Search](https://natalypoida-movie-search.netlify.app/)         
 - [Fancy Weather](https://natalypoida-fancy-weather.netlify.app/)
 - [Movie search(React)](https://movie-search-reacthooks.netlify.app/)
 - [Quick quiz](https://quick-quizz.netlify.app)          
             
### summary ###
I am a novice front-end developer. In June 2020 I completed the “JavaScript Development Online” course at the RSSchool. There Ilearned how to build adaptive web pages and web applications, and how to work with APIs and Git. I keep improving my skills through self-education by watching relevant YouTube channels, and readingpopular programming blogs and books. For example Youtube channels: Vladilen Minin, DesignCourse,RSSchool, Glo Academy, Web Dev Simplified;blogs: Medium Daily Digest, FreeCodeCamp, Community-Z, GeekBrains. I improve the quality of my code every day by working on new self-assigned projects, taking online quizzes, and participating in short intensive online lessons. 

### education ###

**Karaganda State University, Kazakhstan,** Diploma of High Education(equivalent to Bachelor of Education) in Primary Education, Primary School Teacher (1998-2002)

### additional education ###

- **Lewis School of English,** Southampton, England (2006)
- **HTML Acacdemy** (May, 2018 - September, 2019)
- **Codecademy** (February 2019 - September, 2019)
- **The Rolling Scopes: «JavaScript Development Online»** (September, 2019 - June 2020)
         
## skills ##
HTML, HTML5, CSS, JavaScript, ECMAScript 5, REACT(beginner)

**Example of code:**
```html
<div class="description" id="description">
            <h3>АУДИОВЫЗОВ</h3>
            <p>Эта игра поможет тебе в тренировке навыков аудирования - восприятия на слух английских слов.</p>
            <p>Выбери уровень английского языка:</p>
            <select id="select">
                <option value="0" selected>Уровень 1 - Начальный</option>
                <option value="1">Уровень 2 - Базовый</option>
                <option value="2">Уровень 3 - Средий</option>
                <option value="3">Уровень 4 - Выше среднего</option>
                <option value="4">Уровень 5 - Продвинутый</option>
                <option value="5">Уровень 6 - Опытный</option>
            </select>
        </div>
```

```css
*,
*::before,
*::after {
  box-sizing: border-box;
}
:root {
  --hue-neutral: 201;
  --hue-wrong: 0;
  --hue-correct: 100;
}
body {
  font-family: "Roboto", sans-serif;
  --hue: var(--hue-neutral);
  padding: 0;
  margin: 0;
  display: flex;
  width: 100vw;
  height: 100vh;
  justify-content: center;
  align-items: center;
  background-color: hsl(var(--hue), 45%, 75%);
}
```
```javascript
function selectAnswer(element) {
  const selectedButton = element.target;
  const { correct } = selectedButton.dataset;
  setStatusClass(document.body, correct);
  Array.from(answerButtons.children).forEach((button) => {
    setStatusClass(button, button.dataset.correct);
  });
  dontKnowButton.classList.add("hide");
  nextButton.classList.remove("hide");
  if (correct) {
    correctSound.play();
    correctAnswersCount += 1;
  } else {
    wrongSound.play();
    errorCount += 1;
  }
}
```
English Level B1 (according to the test results at the Epam Trainig Centre)
          
**Github:**[https://github.com/natalypoida](https://github.com/natalypoida)
          
