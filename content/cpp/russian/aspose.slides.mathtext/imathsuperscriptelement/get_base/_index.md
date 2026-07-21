---
title: get_Base()
second_title: Aspose.Slides для C++ справочник API
description: Аргумент Base
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/imathsuperscriptelement/get_base/
---
## IMathSuperscriptElement::get_Base() method


Base аргумент

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathSuperscriptElement::get_Base()=0
```

## Примечания


Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto superscript = System::MakeObject<MathematicalText>(u"i");
auto superscriptElement = System::MakeObject<MathSuperscriptElement>(baseElement, superscript);
auto baseElem = superscriptElement->get_Base();
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathSuperscriptElement](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)