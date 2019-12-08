# waveinspiration-rce-framework
Как сделать читабельным исходный код
Оглавление:

Вступление.

I. Теория:

1.1. Переменные;

1.2. Методы и функции;

1.3. Функции/методы возвращающие результат;

1.4. Нетипизованная функции/методы и модификаторы;

1.5. Функции модификаторы и быстрые конвеерные разработчики;

1.6. Вектор Кима;

1.7. Вектор Кима для входящих массивов;

1.8. Именование индексов массивов;

II. Примеры

2.1. Переменные;

2.2. Методы и функции модификаторы;

2.3. Методы и функции возвращающие значения;

2.4. Вектор Кима;

III. Словарь

IV. Эпилог
Вступление

Waveinspiration RCe framework, для краткости именуемый просто RCe framework, теперь благословенен. Да здравствует благословенный RCe framework.

Waveinspiration - это философия уровня результативного мыслительного ядра.
I. Теория: Философия именования переменных и методов Waveinspiration:

1.1. Объявляя переменные, методы и функции, объявляем их типы и назначение прямо в названии, используя типизующие префиксы. (strData)

1.2. Пишем название метода или функции с большой буквы (DataProcessor)

1.3. Объявляя функцию/метод имеющую return, добавляем в префикс, тип данных возвращаемый функцией/методом (strDataProcessor)

1.4. Если мы не знаем что делает функция, или если это функция модификатор, добовляем префиксный минус (_DataProcessor)

1.5. Для функций модификаторов и быстрых конвеерных обработчиков пишем имя и тип входящего и исходящего потоков, отделяя входящий и исходящий потоки префиксными минусами.
(arrFlow1_Processor_arrFlow2)
(_arrFlow1_Processor_arrFlow2)
(_artFlow1_Processor__arrFlow2)

1.6. Вектор Кима (вдохновил Владисан Ким и Руслан Пегов): все входящие в функцию переменные, объявляем с префиксным минусом в префиксе (function(_strData1,_strData2, _...))

1.7. Используем вектор Кима для входящих массивов: _arrData{'_strString':'hello', '_intNumber':10, '_artInnerData':{'_intNum':11}}

1.8. Для именования индексов массивов, используем благословенную философию Waveinspiration.
II. Примеры:

2.1.Переменные:
var strName
var intId
var boolChoice
var arrDataCollection
var objObjectName

2.2.Методы и функции модификаторы (обрабатывающие данные не имеющие return)
public function _ConveerProcess()
public function _ConveerProcess_outputData()
public function _ConveerProcess__outputData()
public function _arrInputData_ProcessData_outputData()
public function
_arrInputData_ProcessData__outputData()

2.3.Методы и функции с return (возвращающие значения)
public function strProcessData()
public function intProcessData()
public function boolIsEqual()
public function objReconstructor()
public function arrMakeDataCollection()

2.4.Вектор Кима:
Именуем переменные поступившие в функцию или метод так: function(_strVariable). Внутри функции обрабатывая переменные передаём их в безопасную переменную, без префиксного минуса.

strProcessData function(_strVariable)

{

strVariable=preg_replace('/[^a-zA-Z0-9\=]/', '', _strVariable);

{

Вектор Кима помогает быстро увидеть уязвимости и устранить их без лишних заморочек.
III. Словарь:

str: string (Строка)
int: integer (Число)
arr: array (Массив)
bool: boolean (Буль)
obj: object (Объект)
_: префиксный минус.
префикс:
суффикс:
окончание:
IV. Эпилог:

Waveinspiration помогает увеличить скорость и качество написания программ.

Waveinspiration помогает и любит вас. Благословенный Waveinspiration RCe framework.

Рекоммендуем к изучению в высших учебных заведениях планеты Земля, как стандарт номер 1 для высокоуровневых языков(с, с++, python, pascal, perl, php, js, bash, delphi, basic, visualBasic, visualPascal, visualC, objectC, ruby on rails, java)
Спасибо за подбор трека Ruby, сколько слушаю хочется подпевать "Он рейлс, он рейлс, он рейлс, он рейлс")

Авторы: Чекмарёв А.А. Циринский И.С. Шаповалова Е.Ю. Тесёлкин М.
© I.S. Zirinskiy[51%] A.A. Chekmarev[39%] K.J.Shapovalova[9%] M.Teselkin[1%] contact: lubimki.ru@yandex.ru 
We are trying to understand around license problem. Every help are welcome. Thank you. ///\///

06.12.2019. Санкт-Петербург. Адмиралтейский р-н., Петроградский р-н., Каменноостровский р-н.
