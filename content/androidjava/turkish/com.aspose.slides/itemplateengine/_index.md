---
title: ITemplateEngine
second_title: Aspose.Slides for Android üzerinden Java API Referansı
description: Şablon ve veri çiftini sonuç çıktısına (genellikle HTML) dönüştüren bir şablon motorunu temsil eder.
type: docs
url: /tr/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

Şablon ve veri çiftini sonuç çıktısına (genellikle HTML) dönüştüren bir şablon motorunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | Şablonu şablon koleksiyonuna ekler. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | Şablonu verilen anahtar ve model nesnesi ile çıktıya dönüştürür. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```


Şablonu şablon koleksiyonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| key | java.lang.String | Şablon koleksiyonundaki şablon için anahtar. |
| template | java.lang.String | Şablon içeriği. |
| modelType | com.aspose.ms.System.Type | Şablon için model nesnesinin türü. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```


Şablonu verilen anahtar ve model nesnesi ile çıktıya dönüştürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| key | java.lang.String | Şablon koleksiyonundaki şablon için anahtar. |
| model | java.lang.Object | Dönüştürme için veri içeren model nesnesi. |

**Dönen Değer:**
java.lang.String - Sonuç çıktısı bir String olarak.