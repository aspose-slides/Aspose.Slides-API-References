---
title: IOleObjectFrame
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 슬라이드에 OLE 개체를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ioleobjectframe/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

슬라이드에 OLE 개체를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | OleObject 이미지 채우기 속성 개체를 반환합니다. |
| [getObjectName()](#getObjectName--) | 객체의 이름을 반환하거나 설정합니다. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | 객체의 이름을 반환하거나 설정합니다. |
| [getEmbeddedData()](#getEmbeddedData--) | OLE 임베디드 데이터에 대한 정보를 가져옵니다. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | OLE 임베디드 데이터에 대한 정보를 설정합니다. |
| [getObjectProgId()](#getObjectProgId--) | 객체의 ProgID를 반환합니다. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | 객체의 ProgID를 반환합니다. |
| [getLinkFileName()](#getLinkFileName--) | 링크된 파일의 전체 경로를 반환합니다. |
| [getLinkPathLong()](#getLinkPathLong--) | 링크된 파일의 전체 경로를 반환합니다. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | 링크된 파일의 전체 경로를 반환합니다. |
| [getLinkPathRelative()](#getLinkPathRelative--) | 존재하는 경우 링크된 파일의 상대 경로를 반환하고, 그렇지 않으면 빈 문자열을 반환합니다. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | 임베디드 OLE 객체의 파일 이름을 반환합니다. |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | 임베디드 OLE 객체의 경로를 반환합니다. |
| [isObjectIcon()](#isObjectIcon--) | 객체가 아이콘으로 표시되는지 여부를 결정합니다. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | 객체가 아이콘으로 표시되는지 여부를 결정합니다. |
| [isObjectLink()](#isObjectLink--) | 객체가 외부 파일에 링크되어 있는지 여부를 결정합니다. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | 프레젠테이션이 열리거나 인쇄될 때 링크된 임베디드 객체가 자동으로 업데이트되는지 여부를 결정합니다. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | 프레젠테이션이 열리거나 인쇄될 때 링크된 임베디드 객체가 자동으로 업데이트되는지 여부를 결정합니다. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | OleObject 아이콘의 제목을 반환하거나 설정합니다. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | OleObject 아이콘의 제목을 반환하거나 설정합니다. |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

OleObject 이미지 채우기 속성 개체를 반환합니다. 읽기 전용 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**반환:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```

객체의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```

객체의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```

OLE 임베디드 데이터에 대한 정보를 가져옵니다. 읽기 전용 [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**반환:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

OLE 임베디드 데이터에 대한 정보를 설정합니다.

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
>          BufferedInputStream bis = null;
>          DataInputStream dis = null;
>          try {
>              File file = new File("Picture.png");
>              byte[] bytes = new byte[(int) file.length()];
>              bis = new BufferedInputStream(new FileInputStream(file));
>              dis = new DataInputStream(bis);
>              dis.readFully(bytes);
>              IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(bytes, "png");
>              oof.setEmbeddedData(newData);
>          } finally {
>              if (dis != null) {
>                  dis.close();
>              if (bis != null)
>                  bis.close();
>              }
>          }
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 임베디드 데이터 [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) |

--------------------

이 메서드는 새 데이터를 반영하도록 객체의 속성을 변경하고 IsObjectLink 플래그를 false로 설정하여 OLE 객체가 임베디드됨을 나타냅니다. |
### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```

객체의 ProgID를 반환합니다. 읽기 전용 String.

**반환:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```

객체의 ProgID를 반환합니다. 읽기 전용 String.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```

링크된 파일의 전체 경로를 반환합니다. 짧은 파일 이름이 사용됩니다. 읽기 전용 String.

**반환:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

링크된 파일의 전체 경로를 반환합니다. 긴 파일 이름이 사용됩니다. 읽기/쓰기 String.

**반환:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

링크된 파일의 전체 경로를 반환합니다. 긴 파일 이름이 사용됩니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```

존재하는 경우 링크된 파일의 상대 경로를 반환하고, 그렇지 않으면 빈 문자열을 반환합니다. 읽기 전용 String.

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

Ppt 프레젠테이션에서 일부 Ole 객체 링크는 상대 경로를 가질 수 있습니다.

**반환:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```

임베디드 OLE 객체의 파일 이름을 반환합니다.

**반환:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```

임베디드 OLE 객체의 경로를 반환합니다.

**반환:**
java.lang.String
### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```

객체가 아이콘으로 표시되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```

객체가 아이콘으로 표시되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```

객체가 외부 파일에 링크되어 있는지 여부를 결정합니다. 읽기 전용 boolean.

**반환:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```

프레젠테이션이 열리거나 인쇄될 때 링크된 임베디드 객체가 자동으로 업데이트되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```

프레젠테이션이 열리거나 인쇄될 때 링크된 임베디드 객체가 자동으로 업데이트되는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```

OleObject 아이콘의 제목을 반환하거나 설정합니다. 읽기/쓰기 String.

--------------------

IsObjectIcon == false인 경우 이 값은 무시됩니다. 문자열은 OLE 아이콘의 크기에 따라 잘릴 수 있습니다.

**반환:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```

OleObject 아이콘의 제목을 반환하거나 설정합니다. 읽기/쓰기 String.

--------------------

IsObjectIcon == false인 경우 이 값은 무시됩니다. 문자열은 OLE 아이콘의 크기에 따라 잘릴 수 있습니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |