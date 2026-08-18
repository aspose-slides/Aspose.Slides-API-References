---
title: VbaReferenceFactory
second_title: Java için Aspose.Slides API Referansı
description: COM arayüzü üzerinden VBA proje referansları oluşturmayı sağlar
type: docs
url: /tr/com.aspose.slides/vbareferencefactory/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

COM arabirimi aracılığıyla VBA proje referansları oluşturmayı sağlar
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getInstance()](#getInstance--) | VBA proje referansları fabrikası statik örneği. |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Yeni OLE Automation tür kitaplığı referansı oluşturur. |
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


Yeni OLE Automation tür kitaplığı referansı oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**Döndürür:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Yeni OLE Automation tür kitaplığı referansı