---
title: AddMathShape()
second_title: Aspose.Slides için C++ API Referansı
description: Matematiksel içeriği barındırmak için yeni bir dikdörtgen otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler.
type: docs
weight: 365
url: /tr/aspose.slides/shapecollection/addmathshape/
---
## ShapeCollection::AddMathShape(float, float, float, float) yöntemi

Matematiksel içeriği barındırmak için yeni bir dikdörtgen otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddMathShape(float x, float y, float width, float height) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Şeklin çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Şeklin çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Şeklin çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Şeklin çerçevesinin yüksekliği, nokta cinsinden. |

### Dönüş Değeri

Yeni oluşturulan [IAutoShape](../../iautoshape/).

## Açıklamalar

Aşağıdaki örnek, PowerPoint [Presentation](../../presentation/) içinde Matematiksel Eşitlik eklemenin nasıl yapılacağını gösterir.
```cpp
auto pres = System::MakeObject<Presentation>();

auto mathShape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 720.0f, 150.0f);
auto mathPortion = mathShape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);
auto mathParagraph = (System::AsCast<MathPortion>(mathPortion))->get_MathParagraph();
auto fraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
mathParagraph->Add(System::MakeObject<MathBlock>(fraction));
auto a2 = System::MakeObject<MathematicalText>(u"a")->SetSuperscript(u"2");
auto b2 = System::MakeObject<MathematicalText>(u"b")->SetSuperscript(u"2");
auto c2 = System::MakeObject<MathematicalText>(u"c")->SetSuperscript(u"2");
auto mathBlock = c2->Join(u"=")->Join(a2)->Join(u"+")->Join(b2); // c^2 = a^2 + b^2
mathParagraph->Add(mathBlock);
pres->Save(u"math.pptx", SaveFormat::Pptx);
```

## Diğer Bağlantılar

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IAutoShape](../../iautoshape/)
* Sınıf [ShapeCollection](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)