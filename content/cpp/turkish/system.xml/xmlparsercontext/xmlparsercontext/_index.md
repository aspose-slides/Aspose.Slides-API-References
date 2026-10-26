---
title: XmlParserContext()
second_title: Aspose.Slides için C++ API Referansı
description: "Belirtilen XmlNameTable, XmlNamespaceManager, xml:lang ve xml:space değerleriyle XmlParserContext sınıfının yeni bir örneğini başlatır."
type: docs
weight: 261
url: /tr/system.xml/xmlparsercontext/xmlparsercontext/
---
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) yapıcı

Belirtilen [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang** ve **xml:space** değerleriyle [XmlParserContext](../) sınıfının yeni bir örneğini başlatır.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) string'leri atomize etmek için kullanılacak. Bu **nullptr** ise, **nsMgr** oluşturmak için kullanılan ad tablosu yerine kullanılır. Atomize edilmiş string'ler hakkında daha fazla bilgi için [XmlNameTable](../../xmlnametable/) bakın. |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) ad alanı bilgisi aramak için kullanılacak, ya da **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang** kapsamı. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | **xml:space** kapsamını gösteren bir XmlSpace değeri. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) yapıcı

Belirtilen [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, **xml:space** ve kodlama ile [XmlParserContext](../) sınıfının yeni bir örneğini başlatır.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) string'leri atomize etmek için kullanılacak. Bu **nullptr** ise, **nsMgr** oluşturulurken kullanılan ad tablosu yerine kullanılır. Atomize string'ler hakkında daha fazla bilgi için [XmlNameTable](../../xmlnametable/) bakın. |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) ad alanı bilgisini aramak için kullanılacak, ya da **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang** kapsamı. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | **xml:space** kapsamını gösteren bir XmlSpace değeri. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Kodlama ayarını gösteren bir Encoding nesnesi. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) yapıcı

Belirtilen [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), temel URI, **xml:lang**, **xml:space** ve belge türü değerleriyle [XmlParserContext](../) sınıfının yeni bir örneğini başlatır.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) string'leri atomize etmek için kullanılacak. Bu **nullptr** ise, **nsMgr** oluşturulurken kullanılan ad tablosu yerine kullanılır. Atomize string'ler hakkında daha fazla bilgi için [XmlNameTable](../../xmlnametable/) bakın. |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) ad alanı bilgisi aramak için kullanılacak, ya da **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | Belge türü deklarasyonunun adı. |
| pubId | const [String](../../../system/string/)\& | Genel tanımlayıcı. |
| sysId | const [String](../../../system/string/)\& | Sistem tanımlayıcı. |
| internalSubset | const [String](../../../system/string/)\& | İç DTD alt kümesi. DTD alt kümesi varlık çözümlemesi için kullanılır, belge doğrulaması için değil. |
| baseURI | const [String](../../../system/string/)\& | XML parçacığı için temel URI (parçacığın yüklendiği konum). |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang** kapsamı. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | **xml:space** kapsamını gösteren bir XmlSpace değeri. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) yapıcı

Belirtilen [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), temel URI, **xml:lang**, **xml:space**, kodlama ve belge türü değerleriyle [XmlParserContext](../) sınıfının yeni bir örneğini başlatır.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) string'leri atomize etmek için kullanılacak. Bu **nullptr** ise, **nsMgr** oluşturulurken kullanılan ad tablosu yerine kullanılır. Atomize string'ler hakkında daha fazla bilgi için [XmlNameTable](../../xmlnametable/) bakın. |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) ad alanı bilgisi aramak için kullanılacak, ya da **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | Belge türü deklarasyonunun adı. |
| pubId | const [String](../../../system/string/)\& | Genel tanımlayıcı. |
| sysId | const [String](../../../system/string/)\& | Sistem tanımlayıcı. |
| internalSubset | const [String](../../../system/string/)\& | İç DTD alt kümesi. DTD varlık çözümlemesi için kullanılır, belge doğrulaması için değil. |
| baseURI | const [String](../../../system/string/)\& | XML parçacığı için temel URI (parçacığın yüklendiği konum). |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang** kapsamı. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | **xml:space** kapsamını gösteren bir XmlSpace değeri. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Kodlama ayarını gösteren bir Encoding nesnesi. |

## Ayrıca Bakınız

* Enum [XmlSpace](../../xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlNameTable](../../xmlnametable/)
* Sınıf [XmlNamespaceManager](../../xmlnamespacemanager/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlParserContext](../)
* Sınıf [Encoding](../../../system.text/encoding/)
* İsim Alanı [System::Xml](../../)
* Library [Aspose.Slides](../../../)