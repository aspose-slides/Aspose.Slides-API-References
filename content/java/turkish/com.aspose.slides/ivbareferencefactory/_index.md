---
title: IVbaReferenceFactory
second_title: Aspose.Slides for Java API Referansı
description: COM arabirimi üzerinden VBA proje referansları oluşturmayı sağlar
type: docs
url: /tr/com.aspose.slides/ivbareferencefactory/
---```
public interface IVbaReferenceFactory
```

COM arabirimi üzerinden VBA proje referansları oluşturmayı sağlar
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Yeni OLE Automation tip kitaplığı referansı oluşturur. |
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public abstract IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Yeni OLE Automation tip kitaplığı referansı oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | VBA proje referansının adı String |
| libid | java.lang.String | Automation tip kitaplığının kimliği String |

**Döndürür:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Yeni OLE Automation tip kitaplığı referansı [IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib)