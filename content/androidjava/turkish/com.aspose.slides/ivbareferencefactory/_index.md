---
title: IVbaReferenceFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create VBA project references via COM interface
type: docs
url: /tr/com.aspose.slides/ivbareferencefactory/
---```
public interface IVbaReferenceFactory
```

COM arabirimi aracılığıyla VBA proje referansları oluşturmayı sağlar
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Yeni bir OLE Automation tip kitaplığı referansı oluşturur. |
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public abstract IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Yeni bir OLE Automation tip kitaplığı referansı oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | VBA proje referansının adı String |
| libid | java.lang.String | Automation tip kitaplığının tanımlayıcısı String |

**Dönüş:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Yeni OLE Automation tip kitaplığı referansı [IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib)