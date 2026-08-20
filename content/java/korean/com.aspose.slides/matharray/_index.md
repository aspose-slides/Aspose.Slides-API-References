---
title: MathArray
second_title: Aspose.Slides for Java API 참조
description: 수식이나 기타 수학 객체의 수직 배열을 지정합니다
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

수식이나 기타 수학 객체의 수직 배열을 지정합니다

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | 지정된 요소를 배열에 배치하여 수학 배열을 생성합니다 |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | 지정된 요소들을 배열에 배치하여 수학 배열을 생성합니다 |
## Methods

| Method | Description |
| --- | --- |
| [getArguments()](#getArguments--) | 배열 항목 집합 |
| [getBaseJustification()](#getBaseJustification--) | 배열을 주변 텍스트에 상대적으로 정렬을 지정합니다. 배열 외부 텍스트는 배열 객체의 아래, 위, 또는 중앙에 정렬될 수 있습니다. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | 배열을 주변 텍스트에 상대적으로 정렬을 지정합니다. 배열 외부 텍스트는 배열 객체의 아래, 위, 또는 중앙에 정렬될 수 있습니다. |
| [getMaximumDistribution()](#getMaximumDistribution--) | 최대 배분. true인 경우 배열은 포함 요소(페이지, 열, 셀 등)의 최대 너비에 맞게 간격이 조정됩니다. |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | 최대 배분. true인 경우 배열은 포함 요소(페이지, 열, 셀 등)의 최대 너비에 맞게 간격이 조정됩니다. |
| [getObjectDistribution()](#getObjectDistribution--) | 객체 배분. true인 경우 배열 내용이 배열 객체의 최대 너비에 맞게 간격이 조정됩니다. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | 객체 배분. true인 경우 배열 내용이 배열 객체의 최대 너비에 맞게 간격이 조정됩니다. |
| [getRowSpacingRule()](#getRowSpacingRule--) | 배열 요소 간 수직 간격 유형. 기본값: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | 배열 요소 간 수직 간격 유형. 기본값: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | 배열 행 간 간격. RowSpacingRule이 3으로 설정된 경우에만 사용됩니다. 정확히는 측정 단위가 포인트이며, Multiple인 경우 측정 단위는 반줄입니다. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | 배열 행 간 간격. RowSpacingRule이 3으로 설정된 경우에만 사용됩니다. 정확히는 측정 단위가 포인트이며, Multiple인 경우 측정 단위는 반줄입니다. |
| [getChildren()](#getChildren--) | 자식 요소 가져오기 |
### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```

지정된 요소를 배열에 배치하여 수학 배열을 생성합니다

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 배열에 배치할 요소 |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```

지정된 요소들을 배열에 배치하여 수학 배열을 생성합니다

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | 배열에 배치할 요소들 |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

배열 항목 집합

--------------------

> ```
> Example:
>  
>  IMMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**Returns:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

배열을 주변 텍스트에 상대적으로 정렬을 지정합니다. 배열 외부 텍스트는 배열 객체의 아래, 위, 또는 중앙에 정렬될 수 있습니다. 기본값: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Returns:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

배열을 주변 텍스트에 상대적으로 정렬을 지정합니다. 배열 외부 텍스트는 배열 객체의 아래, 위, 또는 중앙에 정렬될 수 있습니다. 기본값: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public final boolean getMaximumDistribution()
```

최대 배분. true인 경우 배열은 포함 요소(페이지, 열, 셀 등)의 최대 너비에 맞게 간격이 조정됩니다.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Returns:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public final void setMaximumDistribution(boolean value)
```

최대 배분. true인 경우 배열은 포함 요소(페이지, 열, 셀 등)의 최대 너비에 맞게 간격이 조정됩니다.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public final boolean getObjectDistribution()
```

객체 배분. true인 경우 배열 내용이 배열 객체의 최대 너비에 맞게 간격이 조정됩니다.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Returns:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public final void setObjectDistribution(boolean value)
```

객체 배분. true인 경우 배열 내용이 배열 객체의 최대 너비에 맞게 간격이 조정됩니다.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public final int getRowSpacingRule()
```

배열 요소 간 수직 간격 유형. 기본값: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Returns:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public final void setRowSpacingRule(int value)
```

배열 요소 간 수직 간격 유형. 기본값: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public final long getRowSpacing()
```

배열 행 간 간격. RowSpacingRule이 3으로 설정된 경우에만 사용됩니다. 정확히는 측정 단위가 포인트이며, Multiple인 경우 측정 단위는 반줄입니다. 기본값: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Returns:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public final void setRowSpacing(long value)
```

배열 행 간 간격. RowSpacingRule이 3으로 설정된 경우에만 사용됩니다. 정확히는 측정 단위가 포인트이며, Multiple인 경우 측정 단위는 반줄입니다. 기본값: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

자식 요소 가져오기

**Returns:**
com.aspose.slides.IMathElement[]