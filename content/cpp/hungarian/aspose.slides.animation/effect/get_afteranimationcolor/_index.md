---
title: get_AfterAnimationColor()
second_title: Aspose.Slides C++ API hivatkozás
description: Meghatároz egy animáció utáni színt a hatáshoz. Olvassa el IColorFormat.
type: docs
weight: 248
url: /hu/aspose.slides.animation/effect/get_afteranimationcolor/
---
## Effect::get_AfterAnimationColor() metódus

Meghatároz egy animáció utáni színt a hatáshoz. Olvassa el [IColorFormat](../../../aspose.slides/icolorformat/).

```cpp
System::SharedPtr<IColorFormat> Aspose::Slides::Animation::Effect::get_AfterAnimationColor() override
```

## Megjegyzések

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Az első dia első effektusát lekéri.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Az effektus animáció utáni típusát "Color"-ra módosítja.
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::Color);

// Az effektus animáció utáni színét állítja be.
firstSlideEffect->get_AfterAnimationColor()->set_Color(System::Drawing::Color::get_Green());
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IColorFormat](../../../aspose.slides/icolorformat/)
* Osztály [Effect](../)
* Névtér [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)