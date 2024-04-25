# What is a Method in JavaScript?
Метод — это блок кода, который выполняется только при его вызове. В метод можно передавать данные, называемые параметрами. Методы используются для выполнения определенных действий, и они также известны как функции.
# Create s t r ing in JavaScript
Double Quotes 
```
"Hello"
```
Single Quotes
```
'Hello'
```
Backticks
```
`Hello ${hi}`
```
Метод charAt() возвращает символ по указанному индексу (позиции) в строке. Индекс первого символа равен 0, второму 1, ... Индекс последнего символа - длина строки - 1 .
```
let text = "Hello";
console.log(text.charAt(0)); // 'H'
console.log(text.charAt(1)); // 'e'
console.log(text.charAt(text.length-1)); // 'o'
```
Метод at() принимает целочисленное значение и возвращает новую строку. Этот метод допускает положительные и отрицательные целые числа. Отрицательные целые числа отсчитываются от последнего символа строки.
```
let text1 = "Hello Jane. Lets play football!";
console.log(text1.at(1)); // e
console.log(text1.at(-1)); // !
```
Метод concat() соединяет две или более строк. Метод concat() возвращает новую строку. Метод concat() не изменяет исходную строку
```
let text1 = "Hello";
let text2 = "JavaScript";
let joinText = text1.concat(" ", text2); 
 console.log(joinText);
 ```
 Метод replace() возвращает новую строку с замененными значениями. Метод replace() ищет в строке значение или регулярное выражение. Метод replace() не изменяет исходную строку.
 ```
 let value = "Hello world!";
let changedValue = value.replace("world", "Students"); // replaced world in Students console.log(changedValue); // Hello Students
```
Метод replaceAll() возвращает новую строку, в которой все совпадения шаблона заменяются заменой.
```
let text1= "Hello Jane. Lets check your homeWork Jane";
let replaceText = text1.replaceAll("Jane", "Bro"); // replaces all 'Jane' in 'Bro console.log(replaceText); //Hello Bro. Lets check your homework Bro
```
Метод split() разбивает строку на массив подстрок. Метод split() возвращает новый массив. Метод split() не изменяет исходную строку. Если в качестве разделителя используется (" "), строка разбивается между словами.
```
let text1 = "Hello Jane. Lets play football!";
console.log(text1.split()); // [ 'Hello Jane. Lets play football!! 1 console.log(text1.split(" ")); // [ 'Hello', 'Jane.', 'Lets', 'play', 'football!' ]
```
Метод substring() извлекает символы между двумя индексами (позициями) из строки и возвращает подстроку. Метод substring() извлекает символы от начала до конца (исключая). Метод substring() не изменяет исходную строку. Если start больше end, аргументы меняются местами: (4, 1) = (1, 4). Начальные или конечные значения, меньшие 0, обрабатываются как 0.
```
let text = 'Hello world!';
let sliced = text.substring(1,4) console.log(sliced); // ell
let text = 'Hello world!';
let sliced text.substring(1) console.log(sliced); // ello world!
let text = 'Hello world!';
let sliced text.substring(-1) console.log(sliced); // Hello world!
```
Метод slice() возвращает неглубокую копию части массива и строки в новый объект массива, выбранный от начала до конца (конец не включен), где start и end представляют индекс элементов в этом массиве
```
let text = 'Hello world!';
let sliced = text.slice(1,4) console.log(sliced); // ell
let text = 'Hello world!';
let sliced = text.slice(1) console.log(sliced); // ello world!
let text = 'Hello world!';
let sliced = text.slice(-5,-1) console.log(sliced); // orld
```
Функция Math.floor() округляет число в меньшую сторону до следующего наименьшего целого числа.
```
let a = 43.6
console.log(Math.floor(a))
```
Функция Math.round() возвращает число, округленное до ближайшего целого числа
```
let a = 43.6
console.log(Math.round(a))
```
max() находит максимальное значение среди указанных значений и возвращает его.
```
let num = Math.max(1,2,3,4,5)
console.log(a);
```
# Thanks! 
# Be happy and Smile