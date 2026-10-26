---
title: IOleObjectFrame
second_title: Aspose.Slides için Java API Referansı
description: Bir slaytta OLE nesnesini temsil eder.
type: docs
url: /tr/com.aspose.slides/ioleobjectframe/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

Bir slayt üzerindeki OLE nesnesini temsil eder.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | OleObject görüntü dolgu özellikleri nesnesini döndürür. |
| [getObjectName()](#getObjectName--) | Bir nesnenin adını döndürür veya ayarlar. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Bir nesnenin adını döndürür veya ayarlar. |
| [getEmbeddedData()](#getEmbeddedData--) | OLE gömülü verileri hakkında bilgi alır. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | OLE gömülü verileri hakkında bilgi ayarlar. |
| [getObjectProgId()](#getObjectProgId--) | Bir nesnenin ProgID'sini döndürür. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Bir nesnenin ProgID'sini döndürür. |
| [getLinkFileName()](#getLinkFileName--) | Bağlantılı bir dosyanın tam yolunu döndürür. |
| [getLinkPathLong()](#getLinkPathLong--) | Bağlantılı bir dosyanın tam yolunu döndürür. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Bağlantılı bir dosyanın tam yolunu döndürür. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Var ise bağlantılı dosyanın göreli yolunu döndürür, aksi takdirde boş string döndürür. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Gömülü OLE nesnesinin dosya adını döndürür |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Gömülü OLE nesnesinin yolunu döndürür |
| [isObjectIcon()](#isObjectIcon--) | Bir nesnenin simge olarak görünür olup olmadığını belirler. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Bir nesnenin simge olarak görünür olup olmadığını belirler. |
| [isObjectLink()](#isObjectLink--) | Bir nesnenin dış dosyaya bağlı olup olmadığını belirler. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Bağlantılı gömülü nesnenin sunum açıldığında veya yazdırıldığında otomatik olarak güncellenip güncellenmediğini belirler. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Bağlantılı gömülü nesnenin sunum açıldığında veya yazdırıldığında otomatik olarak güncellenip güncellenmediğini belirler. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | OleObject simgesi için başlığı döndürür veya ayarlar. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | OleObject simgesi için başlığı döndürür veya ayarlar. |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

OleObject görüntü dolgu özellikleri nesnesini döndürür. Yalnızca okunur [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Döndürür:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```

Bir nesnenin adını döndürür veya ayarlar. Okunabilir/yazılabilir String.

**Döndürür:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```

Bir nesnenin adını döndürür veya ayarlar. Okunabilir/yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```

OLE gömülü verileri hakkında bilgi alır. Yalnızca okunur [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Döndürür:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

OLE gömülü verileri hakkında bilgi ayarlar.

--------------------

> ```
> Following example demonstrates how to change OLE embedded data
>  and its type for existing [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) object 
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      OleObjectFrame oof = (OleObjectFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oof != null)
>      {
>          IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(Files.readAllBytes(Paths.get("Picture.png")), "png");
>          oof.setEmbeddedData(newData);
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Gömülü veri [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) |

--------------------

Bu yöntem, nesnenin özelliklerini yeni veriyi yansıtacak şekilde değiştirir ve IsObjectLink bayrağını false olarak ayarlar, OLE nesnesinin gömülü olduğunu gösterir. |
### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```

Bir nesnenin ProgID'sini döndürür. Yalnızca okunur String.

**Döndürür:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```

Bir nesnenin ProgID'sini döndürür. Yalnızca okunur String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```

Bağlantılı bir dosyanın tam yolunu döndürür. Kısa dosya adı kullanılacak. Yalnızca okunur String.

**Döndürür:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Bağlantılı bir dosyanın tam yolunu döndürür. Uzun dosya adı kullanılacak. Okunabilir/yazılabilir String.

**Döndürür:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Bağlantılı bir dosyanın tam yolunu döndürür. Uzun dosya adı kullanılacak. Okunabilir/yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```

Var ise bağlantılı dosyanın göreli yolunu döndürür, aksi takdirde boş string döndürür. Yalnızca okunur String.

--------------------

> ```
> Presentation presentation = new Presentation("demo.ppt");
>  try {
>      IOleObjectFrame oleFrame = (IOleObjectFrame)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oleFrame != null)
>      {
>          System.out.println("The relative path: " + oleFrame.getLinkPathRelative());
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


--------------------

Ppt sunumlarında, bazı Ole nesne bağlantıları göreli bir temsil içerebilir.

**Döndürür:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```

Gömülü OLE nesnesinin dosya adını döndürür

**Döndürür:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```

Gömülü OLE nesnesinin yolunu döndürür

**Döndürür:**
java.lang.String
### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```

Bir nesnenin simge olarak görünür olup olmadığını belirler. Okunabilir/yazılabilir boolean.

**Döndürür:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```

Bir nesnenin simge olarak görünür olup olmadığını belirler. Okunabilir/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```

Bir nesnenin dış dosyaya bağlı olup olmadığını belirler. Yalnızca okunur boolean.

**Döndürür:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```

Bağlantılı gömülü nesnenin sunum açıldığında veya yazdırıldığında otomatik olarak güncellenip güncellenmediğini belirler. Okunabilir/yazılabilir boolean.

**Döndürür:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```

Bağlantılı gömülü nesnenin sunum açıldığında veya yazdırıldığında otomatik olarak güncellenip güncellenmediğini belirler. Okunabilir/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```

OleObject simgesi için başlığı döndürür veya ayarlar. Okunabilir/yazılabilir String.

--------------------

IsObjectIcon == false olduğunda bu değer yok sayılır. Dize, OLE simgesinin boyutuna göre kırpılabilir.

**Döndürür:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```

OleObject simgesi için başlığı döndürür veya ayarlar. Okunabilir/yazılabilir String.

--------------------

IsObjectIcon == false olduğunda bu değer yok sayılır. Dize, OLE simgesinin boyutuna göre kırpılabilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |