---
title: OleObjectFrame
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 슬라이드에 있는 OLE 개체를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/oleobjectframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**All Implemented Interfaces:**
[com.aspose.slides.IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)
```
public class OleObjectFrame extends GraphicalObject implements IOleObjectFrame
```

슬라이드에 있는 OLE 개체를 나타냅니다.

--------------------

> ```
> The following example shows how to accessing OLE Object frames.
>  
>  // PPTX 파일을 프레젠테이션 객체로 로드합니다
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // 첫 번째 슬라이드에 접근합니다
>      ISlide sld = pres.getSlides().get_Item(0);
>      // 모양을 OleObjectFrame으로 캐스팅합니다
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // OLE 개체를 읽고 디스크에 저장합니다
>      if (oleObjectFrame != null) {
>          // 포함된 파일 데이터를 가져옵니다
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // 포함된 파일 확장자를 가져옵니다
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // 추출된 파일을 저장할 경로를 생성합니다
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // 추출된 데이터를 저장합니다
>          FileOutputStream fos = null;
>          try {
>              fos = new FileOutputStream(extractedPath);
>              fos.write(data);
>          } finally {
>              if (fos != null) fos.close();
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | OleObject 이미지 채우기 속성 개체를 반환합니다. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | OleObject 아이콘의 제목을 반환하거나 설정합니다. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | OleObject 아이콘의 제목을 반환하거나 설정합니다. |
| [getObjectName()](#getObjectName--) | 개체의 이름을 반환하거나 설정합니다. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | 개체의 이름을 반환하거나 설정합니다. |
| [getObjectProgId()](#getObjectProgId--) | 개체의 ProgID를 반환합니다. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | 개체의 ProgID를 반환합니다. |
| [getLinkFileName()](#getLinkFileName--) | 연결된 파일의 전체 경로를 반환합니다. |
| [getLinkPathLong()](#getLinkPathLong--) | 연결된 파일의 전체 경로를 반환합니다. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | 연결된 파일의 전체 경로를 반환합니다. |
| [getLinkPathRelative()](#getLinkPathRelative--) | 존재하는 경우 연결된 파일의 상대 경로를 반환하고, 그렇지 않으면 빈 문자열을 반환합니다. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | 포함된 OLE 개체의 파일 이름을 반환합니다 |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | 포함된 OLE 개체의 경로를 반환합니다 |
| [getEmbeddedData()](#getEmbeddedData--) | OLE 포함 데이터에 대한 정보를 가져오거나 설정합니다. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | OLE 포함 데이터에 대한 정보를 설정합니다. |
| [isObjectIcon()](#isObjectIcon--) | 개체가 아이콘으로 표시되는지 여부를 확인합니다. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | 개체가 아이콘으로 표시되는지 여부를 확인합니다. |
| [isObjectLink()](#isObjectLink--) | 개체가 외부 파일에 연결되어 있는지 여부를 확인합니다. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | 프레젠테이션이 열리거나 인쇄될 때 연결된 포함 개체가 자동으로 업데이트되는지 확인합니다. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | 프레젠테이션이 열리거나 인쇄될 때 연결된 포함 개체가 자동으로 업데이트되는지 확인합니다. |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```


OleObject 이미지 채우기 속성 개체를 반환합니다. 읽기 전용 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**반환:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```


OleObject 아이콘의 제목을 반환하거나 설정합니다. 읽기/쓰기 String.

--------------------

IsObjectIcon == false인 경우 이 값은 무시됩니다. 문자열은 Ole 아이콘 크기에 따라 잘릴 수 있습니다.

**반환:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```


OleObject 아이콘의 제목을 반환하거나 설정합니다. 읽기/쓰기 String.

--------------------

IsObjectIcon == false인 경우 이 값은 무시됩니다. 문자열은 Ole 아이콘 크기에 따라 잘릴 수 있습니다.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```


개체의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```


개체의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```


개체의 ProgID를 반환합니다. 읽기 전용 String.

**반환:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```


개체의 ProgID를 반환합니다. 읽기 전용 String.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public final String getLinkFileName()
```


연결된 파일의 전체 경로를 반환합니다. 짧은 파일 이름이 사용됩니다. 읽기 전용 String.

**반환:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```


연결된 파일의 전체 경로를 반환합니다. 긴 파일 이름이 사용됩니다. 읽기/쓰기 String.

**반환:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```


연결된 파일의 전체 경로를 반환합니다. 긴 파일 이름이 사용됩니다. 읽기/쓰기 String.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
```


존재하는 경우 연결된 파일의 상대 경로를 반환하고, 그렇지 않으면 빈 문자열을 반환합니다. 읽기 전용 String.

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

Ppt 프레젠테이션에서 일부 Ole 개체 링크는 상대 경로로 표시될 수 있습니다.

**반환:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public final String getEmbeddedFileLabel()
```


포함된 OLE 개체의 파일 이름을 반환합니다

**반환:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public final String getEmbeddedFileName()
```


포함된 OLE 개체의 경로를 반환합니다

**반환:**
java.lang.String
### getEmbeddedData() {#getEmbeddedData--}
```
public final IOleEmbeddedDataInfo getEmbeddedData()
```


OLE 포함 데이터에 대한 정보를 가져오거나 설정합니다. 읽기/쓰기 [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**반환:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```


OLE 포함 데이터에 대한 정보를 설정합니다.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
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

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 포함 데이터 [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

이 메서드는 개체의 속성을 새 데이터에 맞게 변경하고 IsObjectLink 플래그를 false 로 설정하여 OLE 개체가 포함됨을 나타냅니다. |
### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```


개체가 아이콘으로 표시되는지 여부를 확인합니다. 읽기/쓰기  boolean .

**반환:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```


개체가 아이콘으로 표시되는지 여부를 확인합니다. 읽기/쓰기  boolean .

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```


개체가 외부 파일에 연결되어 있는지 여부를 확인합니다. 읽기 전용  boolean .

**반환:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```


프레젠테이션이 열리거나 인쇄될 때 연결된 포함 개체가 자동으로 업데이트되는지 확인합니다. 읽기/쓰기  boolean .

**반환:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```


프레젠테이션이 열리거나 인쇄될 때 연결된 포함 개체가 자동으로 업데이트되는지 확인합니다. 읽기/쓰기  boolean .

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |