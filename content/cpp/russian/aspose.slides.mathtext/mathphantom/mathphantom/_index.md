---
title: MathPhantom()
second_title: Справочник API Aspose.Slides для C++
description: Создает новый экземпляр класса MathPhantom, используя указанный базовый математический элемент.
type: docs
weight: 144
url: /ru/aspose.slides.mathtext/mathphantom/mathphantom/
---
## MathPhantom::MathPhantom(System::SharedPtr\<IMathElement\>) конструктор

Создает новый экземпляр класса [MathPhantom](../) с использованием указанного базового математического элемента.

```cpp
Aspose::Slides::MathText::MathPhantom::MathPhantom(System::SharedPtr<IMathElement> element)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Базовый [IMathElement](../../imathelement/), чья видимость и расположение будут контролироваться фантомом. Этот элемент определяет содержимое, которое может быть скрыто или показано, при этом всё равно влияет на геометрическое выравнивание окружающей математики. |

## Примечания

Элемент phantom используется для резервирования или подавления визуального пространства своей базовой экспрессии без обязательного отображения её. Он соответствует элементу OMML **<m:phant>**.

Пример:
```cpp
System::SharedPtr<IMathElement> fraction = System::MakeObject<MathFraction>(
    System::MakeObject<MathematicalText>(u"1"),
    System::MakeObject<MathematicalText>(u"2"));
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathPhantom](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)