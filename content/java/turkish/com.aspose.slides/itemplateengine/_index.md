---
title: ITemplateEngine
second_title: Aspose.Slides for Java API Reference
description: Şablon ve veri çiftini (genellikle HTML) sonuç çıktısına dönüştüren bir şablon motorunu temsil eder.
type: docs
url: /tr/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

Şablon ve veri çiftini (genellikle HTML) sonuç çıktısına dönüştüren bir şablon motorunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | Şablonu şablon koleksiyonuna ekler. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | Şablonu verilen anahtar ve model nesnesiyle çıktıya dönüştürür. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```


Şablonu şablon koleksiyonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| key | java.lang.String | Şablon koleksiyonundaki şablonun anahtarı. |
| template | java.lang.String | Şablon içeriği. |
| modelType | com.aspose.ms.System.Type | Şablon için bir model nesnesinin türü. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```


Şablonu verilen anahtar ve model nesnesiyle çıktıya dönüştürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| key | java.lang.String | Şablon koleksiyonundaki şablonun anahtarı. |
| model | java.lang.Object | Dönüşüm için verileri içeren model nesnesi. |

**Dönüş Değeri:**
java.lang.String - Sonuç çıktısı bir String olarak.