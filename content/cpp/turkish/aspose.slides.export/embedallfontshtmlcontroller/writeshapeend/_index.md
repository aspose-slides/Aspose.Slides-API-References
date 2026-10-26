---
title: WriteShapeEnd()
second_title: Aspose.Slides for C++ API Referansı
description: Şeklin render edilmesinden önce çağrılır. Her şekil için bir kez çağrılır. Bu işlev jeneratöre herhangi bir şey yazarsa, mevcut slayt görüntüsü oluşturma tamamlanır, ek html bölümü eklenir ve yeni bir görüntü bir öncekinin üzerine başlatılır.
type: docs
weight: 79
url: /tr/aspose.slides.export/embedallfontshtmlcontroller/writeshapeend/
---
## EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) metodu

Şeklin render edilmesinden önce çağrılır. Her şekil için bir kez çağrılır. Bu işlev jeneratöre herhangi bir şey yazarsa, mevcut slayt görüntüsü oluşturma tamamlanır, ek HTML bölümü eklenir ve yeni bir görüntü bir öncekinin üzerine başlatılır.

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Çıktı nesnesi. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) son render edilen. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IHtmlGenerator](../../ihtmlgenerator/)
* Class [IShape](../../../aspose.slides/ishape/)
* Class [EmbedAllFontsHtmlController](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)