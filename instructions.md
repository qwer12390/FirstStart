# Инструкция по языку MarkDown
## Стилизация текста

## Заголовок 2 уровня

### Заголовок 3 уровня

Обычный текст набирается просто так

**Полужирный текст**

*Курсив*

Цитирование в Mardown 
>Первый уровень цитирования
>>Второй уровень

## Списки
### Ненумерованный

* Лист 1
* Лист 2
### Нумерованный
1. лист
2. лист
3. лист

## Веб-ссылки
Ссылка на лекцию [Введение в контроль версий](https://gb.ru/lessons/402716 "Переход на сайт")

## Вставка изображение
Чтобы вставить изображение в текст, нужно написать:
![комментарий](название файла изображения с расширением)

![картинка](upscaled.jpg)

## Вставка блоков кода
Для вставки строки кода, обрамить `(тильда на англ.раскладке) Пример:
```sh
`print("Hello world")`
```
### Подсветка кода
Для блоков кода можно указать язык программирования.
Используется подсветка синтаксиса из библиотеки 
```linguist```
, которая включает множество языков.

```py
print("Hello, world!")
```