# Calculate-callories
This project is one-page app that runs in a browser. The application allows you to calculate an individual daily calorie allowance. 

This project is programmed using the native JS language. HTML and CSS code is not mine. 

ТЗ:

Состояние по умолчанию
- Выбран мужской пол.
- В полях ввода стоит 0.
- Выбрана «минимальная» физическая активность.
- Кнопка «Рассчитать» неактивна.
- Кнопка сброса данных из полей ввода неактивна.
- Блок с выводом информации о калориях скрыт.
- Кнопка «Рассчитать»
- Становится активна только когда заполнены все поля ввода.
- По клику на кнопку появляется блок с информацией о калориях, если до этого он не был показан. Если блок уже находится на странице, клик по кнопке обновляет расчёты, 
 выводится актуальная информация.

Кнопка «Очистить поля и расчёт» 
- Становится активна, когда хотя бы одно числовое поле заполнено.
- При клике все элементы приложения сбрасываются до состояния по умолчанию: числовые поля очищаются (плейсхолдер 0), пол становится мужской, физическая активность «минимальная», блок с информацией о калориях скрывается.
- 
Формулы
Поддержание веса
Для женщин:

N = (10 × вес в килограммах) + (6,25 × рост в сантиметрах) − (5 × возраст в годах) − 161
Для мужчин:

N = (10 × вес в килограммах) + (6,25 × рост в сантиметрах) − (5 × возраст в годах) + 5
Полученное значение (N) умножаем на коэффициент активности. Результат и будет нормой калорий для поддержания веса.

Коэффициенты активности
- Минимальная: 1.2.
- Низкая: 1.375.
- Средняя: 1.55.
- Высокая: 1.725.
- Очень высокая: 1.9.

Формулы для набора и сброса веса
- Набор веса: прибавляем 15% от нормы к этой норме.
- Сброс веса: вычитаем 15% от нормы из этой нормы.

On english:

Default state

- The male gender is selected.
- There is 0 in the input fields.
- The "minimum" physical activity is selected.
- The "Calculate" button is inactive.
- The button to reset data from the input fields is inactive.
- The block with the output of information about calories is hidden.

The "Calculate" button
- It becomes active only when all the input fields are filled in.
- By clicking on the button, a block with information about calories appears, if it has not been shown before. If the block is already on the page, clicking on the button updates the calculations, and up-to-date information is displayed.

  
The "Clear fields and calculation" button
- It becomes active when at least one numeric field is filled in.
- When clicked, all elements of the application are reset to the default state: numeric fields are cleared (placeholder 0), gender becomes male, physical activity is "minimal", the block with information about calories is hidden.
- 
Weight Maintenance Formulas For Women:

N = (10 × weight in kilograms) + (6.25 × height in centimeters) − (5 × age in years) − 161 For men:

N = (10 × weight in kilograms) + (6.25 × height in centimeters) − (5 × age in years) + 5 The resulting value (N) is multiplied by the activity coefficient. The result will be the norm of calories to maintain weight.

Activity coefficients

- Minimum: 1.2.
- Low: 1.375.
- Average: 1.55.
- High: 1.725.
- Very high: 1.9.
- Formulas for weight gain and loss

- Weight gain: we add 15% of the norm to this norm.
- Weight loss: subtract 15% of the norm from this norm.


File's descriptions:
- index.html - html
- Folders: css, fonts и img - the static resources necessary for registration are found;
- Folder js - js scripts.
