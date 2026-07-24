---
title: Compile()
second_title: Aspose.Slides için C++ API Referansı
description: XML SchemaObject Model (SOM)'u doğrulama için şema bilgisine derler. Programatik olarak oluşturulan SOM'un sözdizimsel ve anlamsal yapısını kontrol etmek için kullanılır. Anlamsal doğrulama denetimi derleme sırasında gerçekleştirilir.
type: docs
weight: 352
url: /tr/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) metodu


XML [Schema](../../)[Object](../../../system/object/) Modelini (SOM) doğrulama için şema bilgisine derler. Programatik olarak oluşturulmuş SOM'un sözdizimsel ve anlamsal yapısını kontrol etmek için kullanılır. Anlamsal doğrulama denetimi derleme sırasında gerçekleştirilir.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | XML [Schema](../../) doğrulama hatalarıyla ilgili bilgileri alan doğrulama olayı işleyicisi. |

## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) metodu


XML [Schema](../../)[Object](../../../system/object/) Modelini (SOM) doğrulama için şema bilgisine derler. Programatik olarak oluşturulmuş SOM'un sözdizimsel ve anlamsal yapısını kontrol etmek için kullanılır. Anlamsal doğrulama denetimi derleme sırasında gerçekleştirilir.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | XML [Schema](../../) doğrulama hatalarıyla ilgili bilgileri alan doğrulama olayı işleyicisi. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | **include** ve **import** öğelerinde başvurulan ad alanları çözülmek için kullanılan [XmlResolver](../../../system.xml/xmlresolver/). |

## İlgili

* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlSchema](../)
* Sınıf [XmlResolver](../../../system.xml/xmlresolver/)
* Ad alanı [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)