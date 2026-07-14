---
title: IMathArray
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 방정식이나 기타 수학 객체의 수직 배열을 지정합니다.
type: docs
url: /ko/com.aspose.slides/imatharray/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

방정식이나 기타 수학 객체의 수직 배열을 지정합니다.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getArguments()](#getArguments--) | 배열의 항목 집합 |
| [getBaseJustification()](#getBaseJustification--) | 배열을 주변 텍스트에 상대적으로 정렬하도록 지정합니다. 배열 외부의 텍스트는 배열 객체의 하단, 상단 또는 중앙에 정렬될 수 있습니다. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | 배열을 주변 텍스트에 상대적으로 정렬하도록 지정합니다. 배열 외부의 텍스트는 배열 객체의 하단, 상단 또는 중앙에 정렬될 수 있습니다. |
| [getMaximumDistribution()](#getMaximumDistribution--) | 최대 분배. true인 경우, 배열은 포함 요소(페이지, 열, 셀 등)의 최대 너비에 맞게 배치됩니다. |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | 최대 분배. true인 경우, 배열은 포함 요소(페이지, 열, 셀 등)의 최대 너비에 맞게 배치됩니다. |
| [getObjectDistribution()](#getObjectDistribution--) | 객체 분배. true인 경우, 배열의 내용이 배열 객체의 최대 너비에 맞게 배치됩니다. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | 객체 분배. true인 경우, 배열의 내용이 배열 객체의 최대 너비에 맞게 배치됩니다. |
| [getRowSpacingRule()](#getRowSpacingRule--) | 배열 요소 사이의 수직 간격 유형 |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | 배열 요소 사이의 수직 간격 유형 |
| [getRowSpacing()](#getRowSpacing--) | 배열 행 사이의 간격. RowSpacingRule이 3으로 설정된 경우에만 사용됩니다. 이 경우 측정 단위는 포인트이며, Multiple인 경우 절반 줄 단위입니다. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | 배열 행 사이의 간격. RowSpacingRule이 3으로 설정된 경우에만 사용됩니다. 이 경우 측정 단위는 포인트이며, Multiple인 경우 절반 줄 단위입니다. |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

배열의 항목 집합

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**반환값:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)

### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

배열을 주변 텍스트에 상대적으로 정렬하도록 지정합니다. 배열 외부의 텍스트는 배열 객체의 하단, 상단 또는 중앙에 정렬될 수 있습니다. 기본값: Center

--------------------

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
public abstract void setBaseJustification(int value)
```

배열을 주변 텍스트에 상대적으로 정렬하도록 지정합니다. 배열 외부의 텍스트는 배열 객체의 하단, 상단 또는 중앙에 정렬될 수 있습니다. 기본값: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public abstract boolean getMaximumDistribution()
```

최대 분배. true인 경우, 배열은 포함 요소(페이지, 열, 셀 등)의 최대 너비에 맞게 배치됩니다.

--------------------

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
public abstract void setMaximumDistribution(boolean value)
```

최대 분배. true인 경우, 배열은 포함 요소(페이지, 열, 셀 등)의 최대 너비에 맞게 배치됩니다.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public abstract boolean getObjectDistribution()
```

객체 분배. true인 경우, 배열의 내용이 배열 객체의 최대 너비에 맞게 배치됩니다.

--------------------

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
public abstract void setObjectDistribution(boolean value)
```

객체 분배. true인 경우, 배열의 내용이 배열 객체의 최대 너비에 맞게 배치됩니다.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public abstract int getRowSpacingRule()
```

배열 요소 사이의 수직 간격 유형

--------------------

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
public abstract void setRowSpacingRule(int value)
```

배열 요소 사이의 수직 간격 유형

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public abstract long getRowSpacing()
```

배열 행 사이의 간격. RowSpacingRule이 3으로 설정된 경우에만 사용됩니다. 이 경우 측정 단위는 포인트이며, Multiple인 경우 절반 줄 단위입니다. 기본값: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**반환값:**
long

### setRowSpacing(long value) {#setRowSpacing-long-}
```
public abstract void setRowSpacing(long value)
```

배열 행 사이의 간격. RowSpacingRule이 3으로 설정된 경우에만 사용됩니다. 이 경우 측정 단위는 포인트이며, Multiple인 경우 절반 줄 단위입니다. 기본값: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | long |  |