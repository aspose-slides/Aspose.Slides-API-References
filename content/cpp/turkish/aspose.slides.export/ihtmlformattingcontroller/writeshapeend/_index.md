---
title: WriteShapeEnd()
second_title: Aspose.Slides for C++ API Referansı
description: Şeklin render edilmesinden önce çağrılır. Her şekil için bir kez çağrılır. Bu işlev jeneratöre bir şeyler yazarsa, mevcut slayt görüntüsü oluşturma tamamlanır, eklenen html fragmenti eklenir ve yeni görüntü öncekinin üzerine başlatılır.
type: docs
weight: 66
url: /tr/aspose.slides.export/ihtmlformattingcontroller/writeshapeend/
---
## IHtmlFormattingController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) metodu

Şeklin render edilmesinden önce çağrılır. Her şekil için bir kez çağrılır. Bu işlev jeneratöre bir şeyler yazarsa, mevcut slayt görüntüsü oluşturma tamamlanır, eklenen html parçacığı eklenir ve yeni görüntü öncekinin üzerine başlatılır.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Çıktı nesnesi. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) son render edilen. |

## İlgili

* Tip tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IHtmlGenerator](../../ihtmlgenerator/)
* Sınıf [IShape](../../../aspose.slides/ishape/)
* Sınıf [IHtmlFormattingController](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)