---
title: Add()
second_title: Aspose.Slides для C++ справочник API
description: Добавляет подпись в конец коллекции.
type: docs
weight: 53
url: /ru/aspose.slides/digitalsignaturecollection/add/
---
## DigitalSignatureCollection::Add(System::SharedPtr\<IDigitalSignature\>) метод


Добавляет подпись в конец коллекции.

```cpp
void Aspose::Slides::DigitalSignatureCollection::Add(System::SharedPtr<IDigitalSignature> signature) override
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| signature | [System::SharedPtr](../../../system/sharedptr/)\<[IDigitalSignature](../../idigitalsignature/)\> | Подпись, которую нужно добавить. |
## Примечания



```cpp
auto pres = System::MakeObject<Presentation>();
auto signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
signature->set_Comments(u"Aspose.Slides digital signing test.");
pres->get_DigitalSignatures()->Add(signature);
pres->Save(u"SomePresentationSigned.pptx", SaveFormat::Pptx);
```


## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IDigitalSignature](../../idigitalsignature/)
* Класс [DigitalSignatureCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)