---
title: PptOptions
second_title: Java API를 통한 Android용 Aspose.Slides 참조
description: 프레젠테이션을 PPT 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.
type: docs
url: /ko/com.aspose.slides/pptoptions/
---
**상속:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**구현된 모든 인터페이스:**
[com.aspose.slides.IPptOptions](../../com.aspose.slides/ipptoptions), java.lang.Cloneable
```
public class PptOptions extends SaveOptions implements IPptOptions, Cloneable
```

프레젠테이션을 PPT 형식으로 저장하는 방식을 제어하는 옵션을 제공합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PptOptions()](#PptOptions--) |  |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | 루트 디렉터리 항목에 저장되는 개체 클래스 GUID(CLSID)를 나타냅니다. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | 루트 디렉터리 항목에 저장되는 개체 클래스 GUID(CLSID)를 나타냅니다. |

### PptOptions() {#PptOptions--}
```
public PptOptions()
```

### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public final UUID getRootDirectoryClsid()
```

루트 디렉터리 항목에 저장되는 개체 클래스 GUID(CLSID)를 나타냅니다. 문서의 애플리케이션을 COM으로 활성화하는 데 사용할 수 있습니다. 기본값은 '64818D11-4F9B-11CF-86EA-00AA00B929E8'이며, 이는 'Microsoft Powerpoint.Slide.8'에 해당합니다.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// CLSID를 'Microsoft Powerpoint.Show.8'로 설정합니다
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
public final void setRootDirectoryClsid(UUID value)
```

루트 디렉터리 항목에 저장되는 개체 클래스 GUID(CLSID)를 나타냅니다. 문서의 애플리케이션을 COM으로 활성화하는 데 사용할 수 있습니다. 기본값은 '64818D11-4F9B-11CF-86EA-00AA00B929E8'이며, 이는 'Microsoft Powerpoint.Slide.8'에 해당합니다.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// CLSID를 'Microsoft Powerpoint.Show.8'로 설정합니다
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.util.UUID |  |