---
title: OleObjectFrame
second_title: Aspose.Slides for Java API Referansı
description: Bir slaytta OLE nesnesini temsil eder.
type: docs
url: /tr/com.aspose.slides/oleobjectframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**All Implemented Interfaces:**
[com.aspose.slides.IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)
```
public class OleObjectFrame extends GraphicalObject implements IOleObjectFrame
```

Bir slaytta OLE nesnesini temsil eder.

--------------------

> ```
> The following example shows how to accessing OLE Object frames.
>  
>  // PPTX'i bir sunum nesnesine yükler
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // İlk slayta erişir
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Şekli OleObjectFrame'e dönüştürür
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // OLE nesnesini okur ve diske yazar
>      if (oleObjectFrame != null) {
>          // Gömülü dosya verilerini alır
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // Gömülü dosya uzantısını alır
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // Alınan dosyayı kaydetmek için bir yol oluşturur
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // Alınan verileri kaydeder
>          Files.write(Paths.get(extractedPath), data);
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | OleObject görüntü doldurma özellikleri nesnesini döndürür. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | OleObject simgesi için başlığı döndürür veya ayarlar. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | OleObject simgesi için başlığı döndürür veya ayarlar. |
| [getObjectName()](#getObjectName--) | Bir nesnenin adını döndürür veya ayarlar. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Bir nesnenin adını döndürür veya ayarlar. |
| [getObjectProgId()](#getObjectProgId--) | Bir nesnenin ProgID'sini döndürür. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Bir nesnenin ProgID'sini döndürür. |
| [getLinkFileName()](#getLinkFileName--) | Bağlantılı dosyanın tam yolunu döndürür. |
| [getLinkPathLong()](#getLinkPathLong--) | Bağlantılı dosyanın tam yolunu döndürür. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Bağlantılı dosyanın tam yolunu döndürür. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Var ise bağlantılı dosyanın göreli yolunu, aksi takdirde boş bir dize döndürür. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Gömülü OLE nesnesinin dosya adını döndürür |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Gömülü OLE nesnesinin yolunu döndürür |
| [getEmbeddedData()](#getEmbeddedData--) | OLE gömülü verileri hakkında bilgiyi alır veya ayarlar. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | OLE gömülü verileri hakkında bilgiyi ayarlar. |
| [isObjectIcon()](#isObjectIcon--) | Bir nesnenin simge olarak görünüp görünmediğini belirler. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Bir nesnenin simge olarak görünüp görünmediğini belirler. |
| [isObjectLink()](#isObjectLink--) | Bir nesnenin dış dosyaya bağlı olup olmadığını belirler. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Bağlantılı gömülü nesnenin sunum açıldığında veya yazdırıldığında otomatik olarak güncellenip güncellenmediğini belirler. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Bağlantılı gömülü nesnenin sunum açıldığında veya yazdırıldığında otomatik olarak güncellenip güncellenmediğini belirler. |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```


OleObject görüntü doldurma özellikleri nesnesini döndürür. Salt okunur [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Döndürür:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```


OleObject simgesi için başlığı döndürür veya ayarlar. Okuma/yazma String.

--------------------

IsObjectIcon == false olduğunda bu değer yok sayılır. Dize, Ole simgesinin boyutuna göre kırpılabilir.

**Döndürür:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```


OleObject simgesi için başlığı döndürür veya ayarlar. Okuma/yazma String.

--------------------

IsObjectIcon == false olduğunda bu değer yok sayılır. Dize, Ole simgesinin boyutuna göre kırpılabilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```


Bir nesnenin adını döndürür veya ayarlar. Okuma/yazma String.

**Döndürür:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```


Bir nesnenin adını döndürür veya ayarlar. Okuma/yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```


Bir nesnenin ProgID'sini döndürür. Salt okunur String.

**Döndürür:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```


Bir nesnenin ProgID'sini döndürür. Salt okunur String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkFileName() {#getLinkFileName--}
```
public final String getLinkFileName()
```


Bağlantılı dosyanın tam yolunu döndürür. Kısa dosya adı kullanılacaktır. Salt okunur String.

**Döndürür:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```


Bağlantılı dosyanın tam yolunu döndürür. Uzun dosya adı kullanılacaktır. Okuma/yazma String.

**Döndürür:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```


Bağlantılı dosyanın tam yolunu döndürür. Uzun dosya adı kullanılacaktır. Okuma/yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
```


Var ise bağlantılı dosyanın göreli yolunu, aksi takdirde boş bir dize döndürür. Salt okunur String.

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

Ppt sunumlarında, bazı Ole nesne bağlantıları göreli bir temsile sahip olabilir.

**Döndürür:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public final String getEmbeddedFileLabel()
```


Gömülü OLE nesnesinin dosya adını döndürür

**Döndürür:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public final String getEmbeddedFileName()
```


Gömülü OLE nesnesinin yolunu döndürür

**Döndürür:**
java.lang.String
### getEmbeddedData() {#getEmbeddedData--}
```
public final IOleEmbeddedDataInfo getEmbeddedData()
```


OLE gömülü verileri hakkında bilgiyi alır veya ayarlar. Okuma/yazma [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Döndürür:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```


OLE gömülü verileri hakkında bilgiyi ayarlar.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
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
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Embedded data [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

Bu yöntem, nesnenin özelliklerini yeni verileri yansıtacak şekilde değiştirir ve IsObjectLink bayrağını false olarak ayarlar; bu, OLE nesnesinin gömülü olduğunu gösterir. |
### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```


Bir nesnenin simge olarak görünüp görünmediğini belirler. Okuma/yazma boolean .

**Döndürür:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```


Bir nesnenin simge olarak görünüp görünmediğini belirler. Okuma/yazma boolean .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```


Bir nesnenin dış dosyaya bağlı olup olmadığını belirler. Salt okunur boolean .

**Döndürür:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```


Bağlantılı gömülü nesnenin sunum açıldığında veya yazdırıldığında otomatik olarak güncellenip güncellenmediğini belirler. Okuma/yazma boolean .

**Döndürür:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```


Bağlantılı gömülü nesnenin sunum açıldığında veya yazdırıldığında otomatik olarak güncellenip güncellenmediğini belirler. Okuma/yazma boolean .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |