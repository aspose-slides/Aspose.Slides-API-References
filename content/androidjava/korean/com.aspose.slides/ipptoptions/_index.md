---
title: IPptOptions
second_title: Android용 Aspose.Slides Java API 레퍼런스
description: 프레젠테이션을 PPT 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.
type: docs
url: /ko/com.aspose.slides/ipptoptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptOptions extends ISaveOptions
```

프레젠테이션을 PPT 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | 루트 디렉터리 항목에 저장된 객체 클래스 GUID(CLSID)를 나타냅니다. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | 루트 디렉터리 항목에 저장된 객체 클래스 GUID(CLSID)를 나타냅니다. |
### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public abstract UUID getRootDirectoryClsid()
```


루트 디렉터리 항목에 저장된 객체 클래스 GUID(CLSID)를 나타냅니다. 문서 애플리케이션의 COM 활성화에 사용할 수 있습니다. 기본값은 '64818D11-4F9B-11CF-86EA-00AA00B929E8'이며, 이는 'Microsoft Powerpoint.Slide.8'에 해당합니다.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// CLSID를 'Microsoft Powerpoint.Show.8'으로 설정
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환값:**  
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public abstract void setRootDirectoryClsid(UUID value)
```


루트 디렉터리 항목에 저장된 객체 클래스 GUID(CLSID)를 나타냅니다. 문서 애플리케이션의 COM 활성화에 사용할 수 있습니다. 기본값은 '64818D11-4F9B-11CF-86EA-00AA00B929E8'이며, 이는 'Microsoft Powerpoint.Slide.8'에 해당합니다.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// CLSID를 'Microsoft Powerpoint.Show.8'으로 설정
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.util.UUID |  |