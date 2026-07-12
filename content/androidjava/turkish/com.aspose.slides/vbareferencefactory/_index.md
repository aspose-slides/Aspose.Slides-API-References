---
title: VbaReferenceFactory
second_title: Java API Referansı üzerinden Android için Aspose.Slides
description: COM arayüzü aracılığıyla VBA proje referansları oluşturmayı sağlar
type: docs
url: /tr/com.aspose.slides/vbareferencefactory/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

COM arabirimi aracılığıyla VBA proje referansları oluşturmayı sağlar
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getInstance()](#getInstance--) | VBA proje referansları fabrikası statik örnek. |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Yeni OLE Automation tip kitaplığı referansı oluşturur. |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```


### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```


VBA proje referansları fabrikası statik örnek. Salt okunur [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**Döndürür:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Yeni OLE Automation tip kitaplığı referansı oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**Döndürür:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Yeni OLE Automation tip kitaplığı referansı