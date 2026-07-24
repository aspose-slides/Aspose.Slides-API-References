---
title: Add()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen URL tarafından konumlandırılan şemayı şema koleksiyonuna ekler.
type: docs
weight: 40
url: /tr/system.xml.schema/xmlschemacollection/add/
---
## XmlSchemaCollection::Add(const String\&, const String\&) method

Verilen URL tarafından konumlandırılan şemayı şema koleksiyonuna ekler.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const String &uri)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | Şema ile ilişkili ad alanı URI'si. XML Şemaları için bu genellikle **targetNamespace** olur. |
| uri | const [String](../../../system/string/)\& | Yüklemek için şemayı belirten URL. |

### Dönüş Değeri

[XmlSchema](../../xmlschema/) şema koleksiyonuna eklenen; eklenen şema bir XDR şemasıysa ya da şemada derleme hataları varsa **nullptr**.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&) method

[XmlReader](../../../system.xml/xmlreader/) içinde bulunan şemayı şema koleksiyonuna ekler.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | Şema ile ilişkili ad alanı URI'si. XML Şemaları için bu genellikle **targetNamespace** olur. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Eklemek için şemayı içeren [XmlReader](../../../system.xml/xmlreader/). |

### Dönüş Değeri

[XmlSchema](../../xmlschema/) şema koleksiyonuna eklenen; eklenen şema bir XDR şemasıysa ya da şemada derleme hataları varsa **nullptr**.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

[XmlReader](../../../system.xml/xmlreader/) içinde bulunan şemayı şema koleksiyonuna ekler. Belirtilen [XmlResolver](../../../system.xml/xmlresolver/) harici kaynakları çözmek için kullanılır.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | Şema ile ilişkili ad alanı URI'si. XML Şemaları için bu genellikle **targetNamespace** olur. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Eklemek için şemayı içeren [XmlReader](../../../system.xml/xmlreader/). |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | **[XmlResolver](../../../system.xml/xmlresolver/)**, **include** ve **import** öğelerinde ya da **x-schema** özniteliğinde (XDR şemaları) başvurulan ad alanlarını çözmek için kullanılır. Bu **nullptr** ise harici referanslar çözülmez. |

### Dönüş Değeri

[XmlSchema](../../xmlschema/) şema koleksiyonuna eklenen; eklenen şema bir XDR şemasıysa ya da şemada derleme hataları varsa **nullptr**.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&) method

[XmlSchema](../../xmlschema/) koleksiyona ekler.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Koleksiyona eklemek için [XmlSchema](../../xmlschema/). |

### Dönüş Değeri

[XmlSchema](../../xmlschema/) nesnesi.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method

[XmlSchema](../../xmlschema/) koleksiyona ekler. Belirtilen [XmlResolver](../../../system.xml/xmlresolver/) harici referansları çözmek için kullanılır.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Koleksiyona eklemek için [XmlSchema](../../xmlschema/). |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | **[XmlResolver](../../../system.xml/xmlresolver/)**, **include** ve **import** öğelerinde başvurulan ad alanlarını çözmek için kullanılır. Bu **nullptr** ise harici referanslar çözülmez. |

### Dönüş Değeri

[XmlSchema](../../xmlschema/) şema koleksiyonuna eklenen.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchemaCollection\>\&) method

Verilen koleksiyonda tanımlı tüm ad alanlarını (ilişkili şemalarıyla birlikte) bu koleksiyona ekler.

```cpp
void System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchemaCollection> &schema)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaCollection](../)\>\& | Bu koleksiyona eklemek istediğiniz [XmlSchemaCollection](../). |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlSchema](../../xmlschema/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlSchemaCollection](../)
* Sınıf [XmlReader](../../../system.xml/xmlreader/)
* Sınıf [XmlResolver](../../../system.xml/xmlresolver/)
* Ad alanı [System::Xml::Schema](../../)
* Kütüphane [Aspose.Slides](../../../)