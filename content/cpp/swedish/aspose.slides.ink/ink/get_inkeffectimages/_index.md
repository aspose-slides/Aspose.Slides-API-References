---
title: get_InkEffectImages()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar samlingen av anpassade bilder som används för att simulera visuella effekter för bläckborstar. Dessa bilder används vid rendering av bläck med specifika InkEffectType-värden, såsom Galaxy, Rainbow osv. Genom att tillhandahålla dina egna bilder kan du kontrollera hur varje bläckëffekt visas.
type: docs
weight: 14
url: /sv/aspose.slides.ink/ink/get_inkeffectimages/
---
## Ink::get_InkEffectImages() metod


Hämtar samlingen av anpassade bilder som används för att simulera visuella effekter för bläckborstar. Dessa bilder används vid rendering av bläck med specifika [InkEffectType](../../inkeffecttype/)-värden, t.ex. Galaxy, Rainbow etc. Genom att tillhandahålla dina egna bilder kan du kontrollera hur varje bläckëffekt visas.

```cpp
static System::SharedPtr<System::Collections::Generic::IDictionary<InkEffectType, System::SharedPtr<IImage>>> Aspose::Slides::Ink::Ink::get_InkEffectImages()
```

## Anmärkningar


Denna egenskap tillåter att ersätta standardtexturer för bläckëffekter med användardefinierade, vilket är särskilt användbart när standardresurser är begränsade av licensiering eller inte är tillgängliga vid körning.

Varje post i ordboken måste associera ett [InkEffectType](../../inkeffecttype/)-värde med ett motsvarande [IImage](../../../aspose.slides/iimage/)-objekt (t.ex. Bitmap, eller ett **Aspose**-bildgränssnitt).

```cpp
System::SharedPtr<IImage> image = Images::FromFile(u"image.png");
Ink::get_InkEffectImages()->Add(InkEffectType::Galaxy, image);
```

## Se även

* Enum [InkEffectType](../../inkeffecttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IDictionary](../../../system.collections.generic/idictionary/)
* Klass [IImage](../../../aspose.slides/iimage/)
* Klass [Ink](../)
* Namnrymd [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)