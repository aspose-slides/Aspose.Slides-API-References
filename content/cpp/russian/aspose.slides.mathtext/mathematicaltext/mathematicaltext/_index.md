---
title: MathematicalText()
second_title: Справочник API Aspose.Slides для C++
description: "Конструктор по умолчанию (создать значение String::Empty)"
type: docs
weight: 40
url: /ru/aspose.slides.mathtext/mathematicaltext/mathematicaltext/
---
## MathematicalText::MathematicalText() конструктор


Конструктор по умолчанию (создать значение String::Empty)

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText()
```

## Примечания


Пример: 
```cpp
auto mathText = System::MakeObject<MathematicalText>();
```

## MathematicalText::MathematicalText(char16_t) конструктор


Создать [MathText](../../) с одним символом

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(char16_t mathSymbol)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathSymbol | char16_t | один символ |
## Примечания



Пример: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u'$');
```

## MathematicalText::MathematicalText(System::String) конструктор


Создать [MathematicalText](../) из текста

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | текстовое значение |
## Примечания



Пример: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
```

## MathematicalText::MathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) конструктор


Создать [MathematicalText](../) из текста и настроек формата

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | текстовое значение |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | настройки формата текста |
## Примечания



Пример: 
```cpp
auto format = [&]{ auto tmp_0 = System::MakeObject<PortionFormat>(); tmp_0->set_FontHeight(12); return tmp_0; }();
auto mathText = System::MakeObject<MathematicalText>(u"x+y", format);
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [MathematicalText](../)
* Класс [String](../../../system/string/)
* Класс [IPortionFormat](../../../aspose.slides/iportionformat/)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)