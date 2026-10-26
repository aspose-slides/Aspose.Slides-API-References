---
title: get_AnimateTextType()
second_title: Aspose.Slides C++ API referencia
description: Meghatározza az effektus animált szöveg típusát. Az alakzat szövege betűnként, szónként vagy egyszerre animálható. Olvassa az AnimateTextType.
type: docs
weight: 274
url: /hu/aspose.slides.animation/ieffect/get_animatetexttype/
---
## IEffect::get_AnimateTextType() method


Meghatározza az effektus animált szöveg típusát. A alakzat szövege animálható betűnként, szónként vagy egyszerre. Olvassa [AnimateTextType](../../animatetexttype/).

```cpp
virtual Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::IEffect::get_AnimateTextType()=0
```

## Megjegyzések



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Az első dia első effektusának lekérése.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Az effektus animált szöveg típusának módosítása "Betűnként"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## Lásd még

* Enum [AnimateTextType](../../animatetexttype/)
* Osztály [IEffect](../)
* Névtere [Aspose::Slides::Animation](../../)
* Könyvtár [Aspose.Slides](../../../)