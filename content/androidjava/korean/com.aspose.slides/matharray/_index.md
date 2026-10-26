---
title: MathArray
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 수식 또는 기타 수학 객체의 수직 배열을 지정합니다
type: docs
url: /ko/com.aspose.slides/matharray/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)
```
public final class MathArray extends MathElementBase implements IMathArray
```

수식 또는 기타 수학 객체의 수직 배열을 지정합니다

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | 수학 배열을 생성하고 지정된 요소를 배열에 배치합니다 |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | 수학 배열을 생성하고 지정된 요소들을 배열에 배치합니다 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getArguments()](#getArguments--) | 배열의 항목 집합 |
| [getBaseJustification()](#getBaseJustification--) | 배열을 주변 텍스트에 상대적으로 정렬을 지정합니다. 배열 외부의 텍스트는 배열 객체의 하단, 상단 또는 중앙에 맞출 수 있습니다. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | 배열을 주변 텍스트에 상대적으로 정렬을 지정합니다. 배열 외부의 텍스트는 배열 객체의 하단, 상단 또는 중앙에 맞출 수 있습니다. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maximum Distribution true인 경우, 배열이 포함 요소(페이지, 열, 셀 등)의 최대 너비에 맞게 배치됩니다. |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maximum Distribution true인 경우, 배열이 포함 요소(페이지, 열, 셀 등)의 최대 너비에 맞게 배치됩니다. |
| [getObjectDistribution()](#getObjectDistribution--) | Object Distribution true인 경우, 배열의 내용이 배열 객체의 최대 너비에 맞게 배치됩니다. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Object Distribution true인 경우, 배열의 내용이 배열 객체의 최대 너비에 맞게 배치됩니다. |
| [getRowSpacingRule()](#getRowSpacingRule--) | 배열 요소 사이의 수직 간격 유형 기본값: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | 배열 요소 사이의 수직 간격 유형 기본값: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | 배열 행 사이의 간격은 RowSpacingRule이 3으로 설정된 경우에만 사용됩니다. 정확히는 단위가 포인트이며, Multiple인 경우 단위가 반줄입니다. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | 배열 행 사이의 간격은 RowSpacingRule이 3으로 설정된 경우에만 사용됩니다. 정확히는 단위가 포인트이며, Multiple인 경우 단위가 반줄입니다. |
| [getChildren()](#getChildren--) | 자식 요소를 가져옵니다 |

### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```

수학 배열을 생성하고 지정된 요소를 배열에 배치합니다

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 배열에 배치할 요소 |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```

수학 배열을 생성하고 지정된 요소들을 배열에 배치합니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | 배열에 배치할 요소들 |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

배열의 항목 집합

> ```
> Example:
>  
>  IMMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**반환값:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

배열을 주변 텍스트에 상대적으로 정렬을 지정합니다. 배열 외부의 텍스트는 배열 객체의 하단, 상단 또는 중앙에 맞출 수 있습니다. 기본값: Center

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**반환값:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

배열을 주변 텍스트에 상대적으로 정렬을 지정합니다. 배열 외부의 텍스트는 배열 객체의 하단, 상단 또는 중앙에 맞출 수 있습니다. 기본값: Center

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public final boolean getMaximumDistribution()
```

Maximum Distribution true인 경우, 배열이 포함 요소(페이지, 열, 셀 등)의 최대 너비에 맞게 배치됩니다.

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**반환값:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public final void setMaximumDistribution(boolean value)
```

Maximum Distribution true인 경우, 배열이 포함 요소(페이지, 열, 셀 등)의 최대 너비에 맞게 배치됩니다.

> ```
> 예시:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public final boolean getObjectDistribution()
```

Object Distribution true인 경우, 배열의 내용이 배열 객체의 최대 너비에 맞게 배치됩니다.

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**반환값:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public final void setObjectDistribution(boolean value)
```

Object Distribution true인 경우, 배열의 내용이 배열 객체의 최대 너비에 맞게 배치됩니다.

> ```
> 예시:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public final int getRowSpacingRule()
```

배열 요소 사이의 수직 간격 유형 기본값: SingleLineGap

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**반환값:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public final void setRowSpacingRule(int value)
```

배열 요소 사이의 수직 간격 유형 기본값: SingleLineGap

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public final long getRowSpacing()
```

배열 행 사이의 간격은 RowSpacingRule이 3으로 설정된 경우에만 사용됩니다. 정확히는 단위가 포인트이며, Multiple인 경우 단위가 반줄입니다. 기본값: 0

> ```
> 예시:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**반환값:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public final void setRowSpacing(long value)
```

배열 행 사이의 간격은 RowSpacingRule이 3으로 설정된 경우에만 사용됩니다. 정확히는 단위가 포인트이며, Multiple인 경우 단위가 반줄입니다. 기본값: 0

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | long |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

자식 요소를 가져옵니다

**반환값:**
com.aspose.slides.IMathElement[]