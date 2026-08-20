---
title: IParagraphFormat
second_title: Aspose.Slides for Java API Reference
description: 이 클래스는 단락 서식 속성을 포함합니다.
type: docs
url: /ko/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

이 클래스는 단락 서식 속성을 포함합니다. [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)와 달리 이 클래스의 모든 속성은 쓰기 가능합니다.

--------------------

이 클래스는 특정 단락에 정의된 단락 서식 속성을 반환하고 조작하는 데 사용됩니다. 이는 값을 가져올 때 상속이 적용되지 않으므로 대부분의 경우 "undefined"(정의되지 않음) 값을 얻게 됨을 의미합니다.

상속된 값을 포함한 실제 서식 매개변수 값을 가져오려면 [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective) 메서드를 사용해야 하며, 이는 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) 인스턴스를 반환합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBullet()](#getBullet--) | 단락의 글머리 기호 형식을 반환합니다. |
| [getDepth()](#getDepth--) | 단락의 깊이를 반환하거나 설정합니다. |
| [setDepth(short value)](#setDepth-short-) | 단락의 깊이를 반환하거나 설정합니다. |
| [getAlignment()](#getAlignment--) | 상속 없이 단락의 텍스트 정렬을 반환하거나 설정합니다. |
| [setAlignment(int value)](#setAlignment-int-) | 상속 없이 단락의 텍스트 정렬을 반환하거나 설정합니다. |
| [getSpaceWithin()](#getSpaceWithin--) | 단락의 기준선 사이의 간격을 반환하거나 설정합니다. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | 단락의 기준선 사이의 간격을 반환하거나 설정합니다. |
| [getSpaceBefore()](#getSpaceBefore--) | 상속 없이 단락의 첫 번째 줄 앞 공간을 반환하거나 설정합니다. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | 상속 없이 단락의 첫 번째 줄 앞 공간을 반환하거나 설정합니다. |
| [getSpaceAfter()](#getSpaceAfter--) | 상속 없이 단락의 마지막 줄 뒤 공간을 반환하거나 설정합니다. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | 상속 없이 단락의 마지막 줄 뒤 공간을 반환하거나 설정합니다. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | 단락에서 동아시아 줄 바꿈이 사용되는지 여부를 확인합니다. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | 단락에서 동아시아 줄 바꿈이 사용되는지 여부를 확인합니다. |
| [getRightToLeft()](#getRightToLeft--) | 단락에서 오른쪽에서 왼쪽으로 쓰기가 사용되는지 여부를 확인합니다. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | 단락에서 오른쪽에서 왼쪽으로 쓰기가 사용되는지 여부를 확인합니다. |
| [getLatinLineBreak()](#getLatinLineBreak--) | 단락에서 라틴 줄 바꿈이 사용되는지 여부를 확인합니다. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | 단락에서 라틴 줄 바꿈이 사용되는지 여부를 확인합니다. |
| [getHangingPunctuation()](#getHangingPunctuation--) | 단락에서 걸이 구두점이 사용되는지 여부를 확인합니다. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | 단락에서 걸이 구두점이 사용되는지 여부를 확인합니다. |
| [getMarginLeft()](#getMarginLeft--) | 상속 없이 단락의 왼쪽 여백을 반환하거나 설정합니다. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | 상속 없이 단락의 왼쪽 여백을 반환하거나 설정합니다. |
| [getMarginRight()](#getMarginRight--) | 상속 없이 단락의 오른쪽 여백을 반환하거나 설정합니다. |
| [setMarginRight(float value)](#setMarginRight-float-) | 상속 없이 단락의 오른쪽 여백을 반환하거나 설정합니다. |
| [getIndent()](#getIndent--) | 상속 없이 단락의 첫 줄 들여쓰기/걸이 들여쓰기를 반환하거나 설정합니다. |
| [setIndent(float value)](#setIndent-float-) | 상속 없이 단락의 첫 줄 들여쓰기/걸이 들여쓰기를 반환하거나 설정합니다. |
| [getDefaultTabSize()](#getDefaultTabSize--) | 상속 없이 기본 탭 크기를 반환하거나 설정합니다. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | 상속 없이 기본 탭 크기를 반환하거나 설정합니다. |
| [getTabs()](#getTabs--) | 단락의 탭 설정을 반환합니다. |
| [getFontAlignment()](#getFontAlignment--) | 상속 없이 단락의 글꼴 정렬을 반환하거나 설정합니다. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | 상속 없이 단락의 글꼴 정렬을 반환하거나 설정합니다. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | 단락의 기본 부분 형식을 반환합니다. |
| [getEffective()](#getEffective--) | 상속이 적용된 실제 단락 서식 데이터를 가져옵니다. |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

단락의 글머리 기호 형식을 반환합니다. 읽기 전용 [IBulletFormat](../../com.aspose.slides/ibulletformat).

**반환:**  
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

단락의 깊이를 반환하거나 설정합니다. 값 0은 정의되지 않은 값을 의미합니다. 읽기/쓰기 short.

**반환:**  
short

### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

단락의 깊이를 반환하거나 설정합니다. 값 0은 정의되지 않은 값을 의미합니다. 읽기/쓰기 short.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

상속 없이 단락의 텍스트 정렬을 반환하거나 설정합니다. 읽기/쓰기 [TextAlignment](../../com.aspose.slides/textalignment).

**반환:**  
int

### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

상속 없이 단락의 텍스트 정렬을 반환하거나 설정합니다. 읽기/쓰기 [TextAlignment](../../com.aspose.slides/textalignment).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

단락의 기준선 사이의 간격을 반환하거나 설정합니다. 양수 값은 백분율을 의미하고, 음수 값은 포인트 단위 크기를 의미합니다. 상속이 적용되지 않습니다. 읽기/쓰기 float.

**반환:**  
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

단락의 기준선 사이의 간격을 반환하거나 설정합니다. 양수 값은 백분율을 의미하고, 음수 값은 포인트 단위 크기를 의미합니다. 상속이 적용되지 않습니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

상속 없이 단락의 첫 번째 줄 앞 공간을 반환하거나 설정합니다. 양수 값은 공백이 차지해야 할 글꼴 크기의 백분율을 지정하고, 음수 값은 포인트 단위 공백 크기를 지정합니다. 읽기/쓰기 float.

**반환:**  
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

상속 없이 단락의 첫 번째 줄 앞 공간을 반환하거나 설정합니다. 양수 값은 공백이 차지해야 할 글꼴 크기의 백분율을 지정하고, 음수 값은 포인트 단위 공백 크기를 지정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

상속 없이 단락의 마지막 줄 뒤 공간을 반환하거나 설정합니다. 양수 값은 공백이 차지해야 할 글꼴 크기의 백분율을 지정하고, 음수 값은 포인트 단위 공백 크기를 지정합니다. 읽기/쓰기 float.

**반환:**  
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

상속 없이 단락의 마지막 줄 뒤 공간을 반환하거나 설정합니다. 양수 값은 공백이 차지해야 할 글꼴 크기의 백분율을 지정하고, 음수 값은 포인트 단위 공백 크기를 지정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

단락에서 동아시아 줄 바꿈이 사용되는지 여부를 판단합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**  
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

단락에서 동아시아 줄 바꿈이 사용되는지 여부를 판단합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

단락에서 오른쪽에서 왼쪽 쓰기가 사용되는지 여부를 판단합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**  
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

단락에서 오른쪽에서 왼쪽 쓰기가 사용되는지 여부를 판단합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

단락에서 라틴 줄 바꿈이 사용되는지 여부를 판단합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**  
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

단락에서 라틴 줄 바꿈이 사용되는지 여부를 판단합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

단락에서 걸이 구두점이 사용되는지 여부를 판단합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환:**  
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

단락에서 걸이 구두점이 사용되는지 여부를 판단합니다. 상속이 적용되지 않습니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

상속 없이 단락의 왼쪽 여백을 반환하거나 설정합니다. 읽기/쓰기 float.

**반환:**  
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

상속 없이 단락의 왼쪽 여백을 반환하거나 설정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

상속 없이 단락의 오른쪽 여백을 반환하거나 설정합니다. 읽기/쓰기 float.

**반환:**  
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

상속 없이 단락의 오른쪽 여백을 반환하거나 설정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

상속 없이 단락의 첫 줄 들여쓰기/걸이 들여쓰기를 반환하거나 설정합니다. 걸이 들여쓰기는 음수 값으로 정의될 수 있습니다. 읽기/쓰기 float.

**반환:**  
float

### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

상속 없이 단락의 첫 줄 들여쓰기/걸이 들여쓰기를 반환하거나 설정합니다. 걸이 들여쓰기는 음수 값으로 정의될 수 있습니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

상속 없이 기본 탭 크기를 반환하거나 설정합니다. 읽기/쓰기 float.

**반환:**  
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

상속 없이 기본 탭 크기를 반환하거나 설정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

단락의 탭 설정을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [ITabCollection](../../com.aspose.slides/itabcollection).

**반환:**  
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

상속 없이 단락의 글꼴 정렬을 반환하거나 설정합니다. 읽기/쓰기 [FontAlignment](../../com.aspose.slides/fontalignment).

**반환:**  
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

상속 없이 단락의 글꼴 정렬을 반환하거나 설정합니다. 읽기/쓰기 [FontAlignment](../../com.aspose.slides/fontalignment).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

단락의 기본 부분 형식을 반환합니다. 상속이 적용되지 않습니다. 읽기 전용 [IPortionFormat](../../com.aspose.slides/iportionformat).

**반환:**  
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

상속이 적용된 실제 단락 서식 데이터를 가져옵니다.

**반환:**  
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).