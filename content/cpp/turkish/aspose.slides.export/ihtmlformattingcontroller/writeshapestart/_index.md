---
title: WriteShapeStart()
second_title: Aspose.Slides for C++ API Referansı
description: Şeklin oluşturulmasından önce çağrılır. Her şekil için bir kez çağrılır. Bu işlev jeneratöre bir şey yazarsa, geçerli slayt görüntüsü oluşturma tamamlanacak, eklenen html parçacığı eklenecek ve yeni görüntü öncekinin üzerine başlatılacaktır.
type: docs
weight: 53
url: /tr/aspose.slides.export/ihtmlformattingcontroller/writeshapestart/
---
## IHtmlFormattingController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) metod

Şeklin oluşturulmasından önce çağrılır. Her şekil için bir kez çağrılır. Bu işlev jeneratöre bir şey yazarsa, geçerli slayt görüntüsü oluşturma tamamlanacak, eklenen html parçacığı eklenecek ve yeni görüntü öncekinin üzerine başlatılacaktır.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Çıktı nesnesi. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) render edilmeye hazır. |

## Ayrıca Bakınız

* Tip tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IHtmlGenerator](../../ihtmlgenerator/)
* Sınıf [IShape](../../../aspose.slides/ishape/)
* Sınıf [IHtmlFormattingController](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)