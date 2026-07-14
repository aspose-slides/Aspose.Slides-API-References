---
title: BulletFormat
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 단락 글머리 기호 서식 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/bulletformat/
---
**상속:**  
[com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**모든 구현된 인터페이스:**  
[com.aspose.slides.IBulletFormat](../../com.aspose.slides/ibulletformat)  
```
public final class BulletFormat extends PVIObject implements IBulletFormat
```

단락 글머리 기호 서식 속성을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getType()](#getType--) | 상속이 없는 단락의 글머리 기호 유형을 반환하거나 설정합니다. |
| [setType(byte value)](#setType-byte-) | 상속이 없는 단락의 글머리 기호 유형을 반환하거나 설정합니다. |
| [getChar()](#getChar--) | 상속이 없는 단락의 글머리 기호 문자를 반환하거나 설정합니다. |
| [setChar(char value)](#setChar-char-) | 상속이 없는 단락의 글머리 기호 문자를 반환하거나 설정합니다. |
| [getFont()](#getFont--) | 상속이 없는 단락의 글머리 기호 글꼴을 반환하거나 설정합니다. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | 상속이 없는 단락의 글머리 기호 글꼴을 반환하거나 설정합니다. |
| [getHeight()](#getHeight--) | 상속이 없는 단락의 글머리 기호 높이를 반환하거나 설정합니다. |
| [setHeight(float value)](#setHeight-float-) | 상속이 없는 단락의 글머리 기호 높이를 반환하거나 설정합니다. |
| [getColor()](#getColor--) | 상속이 없는 단락의 글머리 기호 색상 형식을 반환합니다. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | 상속이 없는 번호 매기기 글머리 기호 그룹에 사용되는 첫 번째 번호를 반환하거나 설정합니다. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | 상속이 없는 번호 매기기 글머리 기호 그룹에 사용되는 첫 번째 번호를 반환하거나 설정합니다. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | 상속이 없는 번호 매기기 글머리 기호의 스타일을 반환하거나 설정합니다. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | 상속이 없는 번호 매기기 글머리 기호의 스타일을 반환하거나 설정합니다. |
| [isBulletHardColor()](#isBulletHardColor--) | 글머리 기호가 자체 색상을 가지고 있는지 또는 단락의 첫 번째 부분에서 색상을 상속받는지 여부를 결정합니다. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) |  |
| [isBulletHardFont()](#isBulletHardFont--) | 글머리 기호가 자체 글꼴을 가지고 있는지 또는 단락의 첫 번째 부분에서 글꼴을 상속받는지 여부를 결정합니다. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | 글머리 기호가 자체 글꼴을 가지고 있는지 또는 단락의 첫 번째 부분에서 글꼴을 상속받는지 여부를 결정합니다. |
| [getPicture()](#getPicture--) | 상속이 없는 단락에서 글머리 기호로 사용되는 그림을 반환합니다. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | 글머리 기호가 활성화된 경우(예: PowerPoint에서 단락 글머리 기호/번호 매기기를 활성화했을 때와 같이) 효과적인 단락 들여쓰기와 MarginLeft에 대한 기본 비영(0이 아닌) 이동값을 설정합니다. |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 글머리 기호 서식 데이터를 가져옵니다. |
| [getVersion()](#getVersion--) |  |

### getType() {#getType--}
```
public final byte getType()
```

상속이 없는 단락의 글머리 기호 유형을 반환하거나 설정합니다. 읽기/쓰기 [BulletType](../../com.aspose.slides/bullettype).

**반환:**  
byte

### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

상속이 없는 단락의 글머리 기호 유형을 반환하거나 설정합니다. 읽기/쓰기 [BulletType](../../com.aspose.slides/bullettype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public final char getChar()
```

상속이 없는 단락의 글머리 기호 문자를 반환하거나 설정합니다. 읽기/쓰기  char .

**반환:**  
char

### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```

상속이 없는 단락의 글머리 기호 문자를 반환하거나 설정합니다. 읽기/쓰기  char .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public final IFontData getFont()
```

상속이 없는 단락의 글머리 기호 글꼴을 반환하거나 설정합니다. 읽기/쓰기 [IFontData](../../com.aspose.slides/ifontdata).

**반환:**  
[IFontData](../../com.aspose.slides/ifontdata)

### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```

상속이 없는 단락의 글머리 기호 글꼴을 반환하거나 설정합니다. 읽기/쓰기 [IFontData](../../com.aspose.slides/ifontdata).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

상속이 없는 단락의 글머리 기호 높이를 반환하거나 설정합니다. 값 Float.NaN은 글머리 기호가 단락의 첫 번째 부분에서 높이를 상속받는다는 것을 결정합니다. 읽기/쓰기  float .

**반환:**  
float

음수 높이 값은 높이가 포인트 단위로 제공됨을 의미하고, 양수 값은 높이가 주변 텍스트의 백분율임을 의미합니다.

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

상속이 없는 단락의 글머리 기호 높이를 반환하거나 설정합니다. 값 Float.NaN은 글머리 기호가 단락의 첫 번째 부분에서 높이를 상속받는다는 것을 결정합니다. 읽기/쓰기  float .

음수 높이 값은 높이가 포인트 단위로 제공됨을 의미하고, 양수 값은 높이가 주변 텍스트의 백분율임을 의미합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

상속이 없는 단락의 글머리 기호 색상 형식을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```

상속이 없는 번호 매기기 글머리 기호 그룹에 사용되는 첫 번째 번호를 반환하거나 설정합니다. 읽기/쓰기  short .

**반환:**  
short

### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```

상속이 없는 번호 매기기 글머리 기호 그룹에 사용되는 첫 번째 번호를 반환하거나 설정합니다. 읽기/쓰기  short .

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```

상속이 없는 번호 매기기 글머리 기호의 스타일을 반환하거나 설정합니다. 읽기/쓰기 [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**반환:**  
byte

### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```

상속이 없는 번호 매기기 글머리 기호의 스타일을 반환하거나 설정합니다. 읽기/쓰기 [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public final byte isBulletHardColor()
```

글머리 기호가 자체 색상을 가지고 있는지 또는 단락의 첫 번째 부분에서 색상을 상속받는지 여부를 결정합니다. **NullableBool.True** if bullet has own color and **NullableBool.False** if bullet inherits color from the first portion in the paragraph. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**  
byte

### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public final void setBulletHardColor(byte value)
```

글머리 기호가 자체 색상을 가지고 있는지 또는 단락의 첫 번째 부분에서 색상을 상속받는지 여부를 결정합니다. **NullableBool.True** if bullet has own color and **NullableBool.False** if bullet inherits color from the first portion in the paragraph. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public final byte isBulletHardFont()
```

글머리 기호가 자체 글꼴을 가지고 있는지 또는 단락의 첫 번째 부분에서 글꼴을 상속받는지 여부를 결정합니다. **NullableBool.True** if bullet has own font and **NullableBool.False** if bullet inherits font from the first portion in the paragraph. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**  
byte

### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public final void setBulletHardFont(byte value)
```

글머리 기호가 자체 글꼴을 가지고 있는지 또는 단락의 첫 번째 부분에서 글꼴을 상속받는지 여부를 결정합니다. **NullableBool.True** if bullet has own font and **NullableBool.False** if bullet inherits font from the first portion in the paragraph. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

상속이 없는 단락에서 글머리 기호로 사용되는 그림을 반환합니다. 읽기 전용 [ISlidesPicture](../../com.aspose.slides/islidespicture).

**반환:**  
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```

글머리 기호가 활성화된 경우(예: PowerPoint에서 단락 글머리 기호/번호 매기기를 활성화했을 때와 같이) 기본 비영(0이 아닌) 이동값을 설정합니다. 글머리 기호가 비활성화된 경우 단락 들여쓰기와 MarginLeft을 재설정합니다(예: PowerPoint에서 단락 글머리 기호/번호 매기기를 비활성화했을 때와 같이). 이동값은 현재 글머리 기호 컨텍스트 – IBulletFormat.Type, .NumberedBulletStyle 및 첫 번째 부분의 FontHeight – 를 기준으로 적용됩니다. 비영 이동값은 현재 단락의 효과적인 Indent 및 MarginLeft에 적용되어 결과 값이 로컬 값이 되도록 합니다.

### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
```

상속이 적용된 효과적인 글머리 기호 서식 데이터를 가져옵니다.

> ```
> 이 예제는 일부 효과적인 글머리 기호 형식 속성을 가져오는 방법을 보여줍니다.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IBulletFormatEffectiveData effectiveBulletFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getBullet().getEffective();
>      System.out.println("Bullet type: " + effectiveBulletFormat.getType());
>      if (effectiveBulletFormat.getType() == BulletType.Numbered)
>      {
>          System.out.println("Numbered style: " + effectiveBulletFormat.getNumberedBulletStyle());
>          System.out.println("Starting number: " + effectiveBulletFormat.getNumberedBulletStartWith());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**  
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - 하나의 [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**반환:**  
long