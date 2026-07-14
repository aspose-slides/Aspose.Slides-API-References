---
title: ParagraphFormat
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 이 클래스는 단락 서식 속성을 포함합니다.
type: docs
url: /ko/com.aspose.slides/paragraphformat/
---
**상속:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**모든 구현된 인터페이스:**  
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)  
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

이 클래스는 단락 서식 속성을 포함합니다. [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)와 달리, 이 클래스의 모든 속성은 쓰기 가능합니다.

--------------------

이 클래스는 특정 단락에 정의된 단락 서식 속성을 반환하고 조작하는 데 사용됩니다. 이는 값을 가져올 때 상속이 적용되지 않으므로 대부분의 경우 “정의되지 않음” 값을 얻게 됨을 의미합니다.

상속된 값을 포함한 실제 서식 매개변수 값을 얻으려면 [getEffective](../../com.aspose.slides/paragraphformat\#getEffective) 메서드를 사용해야 하며, 이 메서드는 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) 인스턴스를 반환합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | 새 [ParagraphFormat](../../com.aspose.slides/paragraphformat) 클래스 인스턴스를 초기화합니다. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBullet()](#getBullet--) | 단락의 글머리표 형식을 반환합니다. |
| [getDepth()](#getDepth--) | 단락의 깊이를 반환하거나 설정합니다. |
| [setDepth(short value)](#setDepth-short-) | 단락의 깊이를 반환하거나 설정합니다. |
| [getAlignment()](#getAlignment--) | 상속이 없는 단락에서 텍스트 정렬을 반환하거나 설정합니다. |
| [setAlignment(int value)](#setAlignment-int-) | 상속이 없는 단락에서 텍스트 정렬을 반환하거나 설정합니다. |
| [getSpaceWithin()](#getSpaceWithin--) | 단락의 기준선 사이 간격을 반환하거나 설정합니다. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | 단락의 기준선 사이 간격을 반환하거나 설정합니다. |
| [getSpaceBefore()](#getSpaceBefore--) | 상속이 없는 단락에서 첫 번째 줄 앞의 공간을 반환하거나 설정합니다. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | 상속이 없는 단락에서 첫 번째 줄 앞의 공간을 반환하거나 설정합니다. |
| [getSpaceAfter()](#getSpaceAfter--) | 상속이 없는 단락에서 마지막 줄 뒤의 공간을 반환하거나 설정합니다. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | 상속이 없는 단락에서 마지막 줄 뒤의 공간을 반환하거나 설정합니다. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | 단락에서 동아시아 줄 바꿈이 사용되는지 여부를 결정합니다. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | 단락에서 동아시아 줄 바꿈이 사용되는지 여부를 결정합니다. |
| [getRightToLeft()](#getRightToLeft--) | 단락에서 오른쪽에서 왼쪽으로 쓰기가 사용되는지 여부를 결정합니다. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | 단락에서 오른쪽에서 왼쪽으로 쓰기가 사용되는지 여부를 결정합니다. |
| [getLatinLineBreak()](#getLatinLineBreak--) | 단락에서 라틴 줄 바꿈이 사용되는지 여부를 결정합니다. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | 단락에서 라틴 줄 바꿈이 사용되는지 여부를 결정합니다. |
| [getHangingPunctuation()](#getHangingPunctuation--) | 단락에서 매달린 구두점이 사용되는지 여부를 결정합니다. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | 단락에서 매달린 구두점이 사용되는지 여부를 결정합니다. |
| [getMarginLeft()](#getMarginLeft--) | 상속이 없는 단락에서 왼쪽 여백을 반환하거나 설정합니다. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | 상속이 없는 단락에서 왼쪽 여백을 반환하거나 설정합니다. |
| [getMarginRight()](#getMarginRight--) | 상속이 없는 단락에서 오른쪽 여백을 반환하거나 설정합니다. |
| [setMarginRight(float value)](#setMarginRight-float-) | 상속이 없는 단락에서 오른쪽 여백을 반환하거나 설정합니다. |
| [getIndent()](#getIndent--) | 상속이 없는 단락에서 첫 줄 들여쓰기/걸려 있는 들여쓰기를 반환하거나 설정합니다. |
| [setIndent(float value)](#setIndent-float-) | 상속이 없는 단락에서 첫 줄 들여쓰기/걸려 있는 들여쓰기를 반환하거나 설정합니다. |
| [getDefaultTabSize()](#getDefaultTabSize--) | 상속이 없는 기본 탭 크기를 반환하거나 설정합니다. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | 상속이 없는 기본 탭 크기를 반환하거나 설정합니다. |
| [getTabs()](#getTabs--) | 단락의 탭을 반환합니다. |
| [getFontAlignment()](#getFontAlignment--) | 상속이 없는 단락에서 글꼴 정렬을 반환하거나 설정합니다. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | 상속이 없는 단락에서 글꼴 정렬을 반환하거나 설정합니다. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | 단락의 기본 구간 형식을 반환합니다. |
| [getEffective()](#getEffective--) | 상속이 적용된 실제 단락 서식 데이터를 가져옵니다. |
| [getVersion()](#getVersion--) |  |

### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```

[ParagraphFormat](../../com.aspose.slides/paragraphformat) 클래스의 새 인스턴스를 초기화합니다.

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```

단락의 글머리표 형식을 반환합니다. 읽기 전용 [IBulletFormat](../../com.aspose.slides/ibulletformat).

**반환:**  
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public final short getDepth()
```

단락의 깊이를 반환하거나 설정합니다. 값 0은 정의되지 않은 값을 의미합니다. 읽기/쓰기 short .

**반환:**  
short

### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```

단락의 깊이를 반환하거나 설정합니다. 값 0은 정의되지 않은 값을 의미합니다. 읽기/쓰기 short .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

상속이 없는 단락에서 텍스트 정렬을 반환하거나 설정합니다. 읽기/쓰기 [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // PPTX 파일을 나타내는 Presentation 객체를 인스턴스화합니다
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // 첫 번째 슬라이드에 액세스합니다
>      ISlide slide = pres.getSlides().get_Item(0);
>      // 슬라이드의 첫 번째와 두 번째 플레이스홀더에 액세스하고 이를 AutoShape으로 형변환합니다
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // 두 플레이스홀더의 텍스트를 변경합니다
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // 플레이스홀더의 첫 번째 단락을 가져옵니다
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // 텍스트 단락을 가운데 정렬합니다
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //프레젠테이션을 PPTX 파일로 저장합니다
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**  
int

### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

상속이 없는 단락에서 텍스트 정렬을 반환하거나 설정합니다. 읽기/쓰기 [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // PPTX 파일을 나타내는 Presentation 객체를 인스턴스화합니다
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // 첫 번째 슬라이드에 액세스합니다
>      ISlide slide = pres.getSlides().get_Item(0);
>      // 슬라이드의 첫 번째와 두 번째 플레이스홀더에 액세스하고 이를 AutoShape으로 형변환합니다
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // 두 플레이스홀더의 텍스트를 변경합니다
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // 플레이스홀더의 첫 번째 단락을 가져옵니다
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // 텍스트 단락을 가운데 정렬합니다
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //프레젠테이션을 PPTX 파일로 저장합니다
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```

단락의 기준선 사이 간격을 반환하거나 설정합니다. 양수 값은 백분율을 의미하고, 음수 값은 포인트 크기를 의미합니다. 상속이 적용되지 않습니다. 읽기/쓰기 float .

**반환:**  
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```

단락의 기준선 사이 간격을 반환하거나 설정합니다. 양수 값은 백분율을 의미하고, 음수 값은 포인트 크기를 의미합니다. 상속이 적용되지 않습니다. 읽기/쓰기 float .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```

상속이 없는 단락에서 첫 번째 줄 앞의 공간을 반환하거나 설정합니다. 양의 값은 글꼴 크기의 백분율을 지정하고, 음의 값은 포인트 크기로 지정합니다. 읽기/쓰기 float .

**반환:**  
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```

상속이 없는 단락에서 첫 번째 줄 앞의 공간을 반환하거나 설정합니다. 양의 값은 글꼴 크기의 백분율을 지정하고, 음의 값은 포인트 크기로 지정합니다. 읽기/쓰기 float .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```

상속이 없는 단락에서 마지막 줄 뒤의 공간을 반환하거나 설정합니다. 양의 값은 글꼴 크기의 백분율을 지정하고, 음의 값은 포인트 크기로 지정합니다. 읽기/쓰기 float .

**반환:**  
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```

상속이 없는 단락에서 마지막 줄 뒤의 공간을 반환하거나 설정합니다. 양의 값은 글꼴 크기의 백분율을 지정하고, 음의 값은 포인트 크기로 지정합니다. 읽기/쓰기 float .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```

단락에서 동아시아 줄 바꿈이 사용되는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**  
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```

단락에서 동아시아 줄 바꿈이 사용되는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```

단락에서 오른쪽에서 왼쪽으로 쓰기가 사용되는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**  
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```

단락에서 오른쪽에서 왼쪽으로 쓰기가 사용되는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```

단락에서 라틴 줄 바꿈이 사용되는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**  
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```

단락에서 라틴 줄 바꿈이 사용되는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```

단락에서 매달린 구두점이 사용되는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**  
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```

단락에서 매달린 구두점이 사용되는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```

상속이 없는 단락에서 왼쪽 여백을 반환하거나 설정합니다. 읽기/쓰기 float .

**반환:**  
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```

상속이 없는 단락에서 왼쪽 여백을 반환하거나 설정합니다. 읽기/쓰기 float .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```

상속이 없는 단락에서 오른쪽 여백을 반환하거나 설정합니다. 읽기/쓰기 float .

**반환:**  
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```

상속이 없는 단락에서 오른쪽 여백을 반환하거나 설정합니다. 읽기/쓰기 float .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public final float getIndent()
```

상속이 없는 단락에서 첫 줄 들여쓰기/걸려 있는 들여쓰기를 반환하거나 설정합니다. 걸려 있는 들여쓰기는 음수 값으로 정의될 수 있습니다. 읽기/쓰기 float .

**반환:**  
float

### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```

상속이 없는 단락에서 첫 줄 들여쓰기/걸려 있는 들여쓰기를 반환하거나 설정합니다. 걸려 있는 들여쓰기는 음수 값으로 정의될 수 있습니다. 읽기/쓰기 float .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```

상속이 없는 기본 탭 크기를 반환하거나 설정합니다. 읽기/쓰기 float .

**반환:**  
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```

상속이 없는 기본 탭 크기를 반환하거나 설정합니다. 읽기/쓰기 float .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```

단락의 탭을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [ITabCollection](../../com.aspose.slides/itabcollection).

**반환:**  
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```

상속이 없는 단락에서 글꼴 정렬을 반환하거나 설정합니다. 읽기/쓰기 [FontAlignment](../../com.aspose.slides/fontalignment).

**반환:**  
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```

상속이 없는 단락에서 글꼴 정렬을 반환하거나 설정합니다. 읽기/쓰기 [FontAlignment](../../com.aspose.slides/fontalignment).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```

단락의 기본 구간 형식을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [IPortionFormat](../../com.aspose.slides/iportionformat).

**반환:**  
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```

상속이 적용된 실제 단락 서식 데이터를 가져옵니다.

--------------------

> ```
> 이 예제는 몇 가지 실제 단락 서식 속성을 가져오는 방법을 보여줍니다.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IParagraphFormatEffectiveData effectiveParagraphFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getEffective();
>  	System.out.println("Text alignment: " + effectiveParagraphFormat.getAlignment());
>  	System.out.println("Indent: " + effectiveParagraphFormat.getIndent());
>  	System.out.println("Bullet type: " + effectiveParagraphFormat.getBullet().getType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**반환:**  
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**반환:**  
long