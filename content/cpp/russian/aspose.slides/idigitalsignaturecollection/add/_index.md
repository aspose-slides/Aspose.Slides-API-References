---
title: Add()
second_title: Aspose.Slides для C++ справка API
description: Добавляет подпись в конец коллекции.
type: docs
weight: 14
url: /ru/aspose.slides/idigitalsignaturecollection/add/
---
## IDigitalSignatureCollection::Add(System::SharedPtr\<IDigitalSignature\>) метод


Добавляет подпись в конец коллекции.

```cpp
virtual void Aspose::Slides::IDigitalSignatureCollection::Add(System::SharedPtr<IDigitalSignature> digitalSignature)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| digitalSignature | [System::SharedPtr](../../../system/sharedptr/)\<[IDigitalSignature](../../idigitalsignature/)\> | Подпись для добавления. |
## Примечания



```cpp
auto pres = System::MakeObject<Presentation>();
auto signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
signature->set_Comments(u"Aspose.Slides digital signing test.");
pres->get_DigitalSignatures()->Add(signature);
pres->Save(u"SomePresentationSigned.pptx", SaveFormat::Pptx);
```


## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IDigitalSignature](../../idigitalsignature/)
* Класс [IDigitalSignatureCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)