---
title: AddTextFrame()
second_title: Aspose.Slides for C++ API Referansı
description: Bir şekle yeni bir TextFrame ekler. Şeklin zaten TextFrame'i varsa, sadece metnini değiştirir.
type: docs
weight: 66
url: /tr/aspose.slides/autoshape/addtextframe/
---
## AutoShape::AddTextFrame(System::String) yöntemi


Yeni bir [TextFrame](../../textframe/) ekler bir şekle. Şeklin zaten [TextFrame](../../textframe/) varsa, sadece metnini değiştirir.

```cpp
System::SharedPtr<ITextFrame> Aspose::Slides::AutoShape::AddTextFrame(System::String text) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Yeni bir [TextFrame](../../textframe/) için varsayılan metin. |
## Açıklamalar



Aşağıdaki örnek kod, PowerPoint [Presentation](../../presentation/) içinde filigran metni eklemenin nasıl yapılacağını gösterir. 
```cpp
auto presentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 150.0f, 50.0f);
System::SharedPtr<ITextFrame> watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
```
 Aşağıdaki örnek, [Slide](../../slide/) üzerinde Metin Kutusu oluşturmanın nasıl yapılacağını gösterir. 
```cpp
// Presentation nesnesini oluşturur
auto pres = System::MakeObject<Presentation>();

// Sunumdaki ilk slaytı alır
auto slide = pres->get_Slides()->idx_get(0);
// Dikdörtgen olarak ayarlanmış bir AutoShape ekler
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
// Dikdörtgene TextFrame ekler
shape->AddTextFrame(u" ");
// Metin çerçevesine erişir
auto txtFrame = shape->get_TextFrame();
// Metin çerçevesi için Paragraph nesnesi oluşturur
auto para = txtFrame->get_Paragraphs()->idx_get(0);
// Paragraf için Portion nesnesi oluşturur
auto portion = para->get_Portions()->idx_get(0);
// Metni ayarlar
portion->set_Text(u"Aspose TextBox");
// Sunumu diske kaydeder
pres->Save(u"TextBox_out.pptx", SaveFormat::Pptx);
```
 Aşağıdaki örnek, Metin Kutusu içinde sütun eklemenin nasıl yapılacağını gösterir. 
```cpp
auto presentation = System::MakeObject<Presentation>();

// Sunumdaki ilk slaytı alır
auto slide = presentation->get_Slides()->idx_get(0);
// Tipi Dikdörtgen olarak ayarlanmış bir AutoShape ekler
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 300.0f, 300.0f);
// Dikdörtgene TextFrame ekler
shape->AddTextFrame(System::String(u"All these columns are limited to be within a single text container -- ") +
                    u"you can add or delete text and the new or remaining text automatically adjusts " +
                    u"itself to flow within the container. You cannot have text flow from one container " +
                    u"to other though -- we told you PowerPoint's column options for text are limited!");
// TextFrame'in metin biçimini alır
auto format = shape->get_TextFrame()->get_TextFrameFormat();
// TextFrame'deki sütun sayısını belirler
format->set_ColumnCount(3);
// Sütunlar arasındaki boşluğu belirler
format->set_ColumnSpacing(10);
// Sunumu kaydeder
presentation->Save(u"ColumnCount.pptx", SaveFormat::Pptx);
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ITextFrame](../../itextframe/)
* Sınıf [String](../../../system/string/)
* Sınıf [AutoShape](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)