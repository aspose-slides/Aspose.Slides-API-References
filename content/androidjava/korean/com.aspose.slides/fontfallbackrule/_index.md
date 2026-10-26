---
title: FontFallBackRule
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 폰트 대체 규칙을 나타냅니다
type: docs
url: /ko/com.aspose.slides/fontfallbackrule/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
```
public class FontFallBackRule implements IFontFallBackRule
```

폰트 대체 규칙을 나타냅니다
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | 새 인스턴스를 생성합니다. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | 새 인스턴스를 생성합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | 새 폰트를 FallBack 폰트 목록에 추가합니다. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | 새 폰트를 FallBack 폰트 목록에 추가합니다. |
| [getRangeStartIndex()](#getRangeStartIndex--) | 연속적인 유니코드 범위의 첫 번째 인덱스를 가져옵니다. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | 연속적인 유니코드 범위의 첫 번째 인덱스를 가져옵니다. |
| [getRangeEndIndex()](#getRangeEndIndex--) | 연속적인 유니코드 범위의 마지막 인덱스를 가져옵니다. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | 연속적인 유니코드 범위의 마지막 인덱스를 가져옵니다. |
| [getCount()](#getCount--) | 범위에 실제로 정의된 폰트 수를 가져옵니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 폰트 이름을 가져옵니다. |
| [clear()](#clear--) | 목록에서 모든 폰트를 제거합니다. |
| [remove(String fontName)](#remove-java.lang.String-) | 목록에서 특정 FallBack 폰트의 첫 번째 항목을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 목록에서 지정된 인덱스의 FallBack 폰트를 제거합니다. |
| [toArray()](#toArray--) | 이 규칙에 대한 모든 FallBack 폰트를 포함하는 배열을 생성하고 반환합니다. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 목록의 지정된 범위에 있는 모든 FallBack 폰트를 포함하는 배열을 생성하고 반환합니다. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | 컬렉션에서 지정된 규칙의 인덱스를 반환합니다. |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```

새 인스턴스를 생성합니다.

--------------------

> ```
> // FantFallBackRule의 새 인스턴스를 하나의 폰트와 함께 생성합니다.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // FantFallBackRule의 새 인스턴스를 여러 폰트와 함께 생성합니다.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startIndex | long | 유니코드 범위의 시작 인덱스 |
| endIndex | long | 유니코드 범위의 끝 인덱스 |
| fontNames | java.lang.String | FallBack용 폰트 이름 또는 이름들(쉼표로 구분) |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```

새 인스턴스를 생성합니다.

--------------------

> ```
> // Create new instance of FantFallBackRule with two fonts
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // Create new instance of FantFallBackRule with several fonts.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startIndex | long | 유니코드 범위의 시작 인덱스 |
| endIndex | long | 유니코드 범위의 끝 인덱스 |
| fontNames | java.lang.String[] | FallBack용 폰트 이름 또는 이름들(쉼표로 구분) |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```

새 폰트를 FallBack 폰트 목록에 추가합니다.

--------------------

> ```
> // FontFallBackRule의 새 인스턴스를 생성합니다
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //규칙에 두 번째 폰트를 추가합니다 
>  newRule.addFallBackFonts("MS Gothic");
>  //규칙에 세 번째와 네 번째 폰트를 추가합니다 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | java.lang.String | FallBack용 폰트 이름 또는 이름들(쉼표로 구분) |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```

새 폰트를 FallBack 폰트 목록에 추가합니다.

--------------------

> ```
> //Create new instance of FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Add of another three fonts to the rule 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontNames | java.lang.String[] | FallBack용 폰트 이름 또는 이름들(쉼표로 구분) |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```

연속적인 유니코드 범위의 첫 번째 인덱스를 가져옵니다.

**반환값:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```

연속적인 유니코드 범위의 첫 번째 인덱스를 가져옵니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```

연속적인 유니코드 범위의 마지막 인덱스를 가져옵니다.

**반환값:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```

연속적인 유니코드 범위의 마지막 인덱스를 가져옵니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```

범위에 실제로 정의된 폰트 수를 가져옵니다. 읽기 전용 int.

**반환값:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```

지정된 인덱스의 폰트 이름을 가져옵니다. 읽기 전용 [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
java.lang.String
### clear() {#clear--}
```
public final void clear()
```

목록에서 모든 폰트를 제거합니다.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```

목록에서 특정 FallBack 폰트의 첫 번째 항목을 제거합니다.

--------------------

> ```
> // 폰트 목록을 포함하는 규칙을 생성합니다.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // 리스트에서 Tahoma를 제거합니다.
>  newRule.remove("Tahoma");
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | java.lang.String | 목록에서 제거할 폰트의 이름. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

목록에서 지정된 인덱스의 FallBack 폰트를 제거합니다.

--------------------

> ```
> // 폰트 목록을 포함하는 규칙을 생성합니다.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //리스트에서 Tahoma를 제거합니다.
>  newRule.remove(2);
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 제거할 폰트의 0 기반 인덱스. |

### toArray() {#toArray--}
```
public final String[] toArray()
```

이 규칙에 대한 모든 FallBack 폰트를 포함하는 배열을 생성하고 반환합니다.

--------------------

> ```
> // 폰트 목록을 포함하는 규칙을 생성합니다.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // 모든 폰트 이름을 배열로 가져옵니다.
>  String[] fontNames = newRule.toArray();
> ```


**반환값:**
java.lang.String[] - Array of String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```

목록의 지정된 범위에 있는 모든 FallBack 폰트를 포함하는 배열을 생성하고 반환합니다.

```
// 폰트 목록을 포함하는 규칙을 생성합니다.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // 마지막 두 개의 폰트 이름을 배열로 가져옵니다.
 String[] fontNames = newRule.toArray(2, 2);
```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startIndex | int | 추가할 첫 번째 폰트의 인덱스. |
| count | int | 추가할 폰트 수. |

**반환값:**
java.lang.String[] - Array of String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```

컬렉션에서 지정된 규칙의 인덱스를 반환합니다.

--------------------

> ```
> // 폰트 목록을 포함하는 규칙을 생성합니다.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Tahoma의 인덱스를 가져옵니다.
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | java.lang.String | 찾을 폰트 이름. |

**반환값:**
int - Index of a font or -1 if font not found in list.