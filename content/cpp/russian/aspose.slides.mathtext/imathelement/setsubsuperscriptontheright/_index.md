---
title: SetSubSuperscriptOnTheRight()
second_title: Aspose.Slides для C++ справочник API
description: Создает нижний и верхний индексы справа
type: docs
weight: 105
url: /ru/aspose.slides.mathtext/imathelement/setsubsuperscriptontheright/
---
## IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) метод


Создает нижний и верхний индексы справа

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Нижний индекс (нижний индекс справа) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Верхний индекс (верхний индекс справа) |

### Возвращаемое значение

Новый математический элемент типа [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Примечания



Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheRight(System::String, System::String) метод


Создает нижний и верхний индексы справа

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript)=0
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Нижний индекс (нижний индекс справа) |
| superscript | [System::String](../../../system/string/) | Верхний индекс (верхний индекс справа) |

### Возвращаемое значение

Новый математический элемент типа [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Примечания



Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Класс [IMathElement](../)
* Класс [String](../../../system/string/)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)