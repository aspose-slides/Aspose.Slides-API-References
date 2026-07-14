---
title: IFontFallBackRule
second_title: Aspose.Slides for Android via Java API Reference
description: Represents font fallback rule
type: docs
url: /ko/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

폰트 대체 규칙을 나타냅니다
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | 새 폰트(들)를 FallBack 폰트 목록에 추가합니다. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | 새 폰트(들)를 FallBack 폰트 목록에 추가합니다. |
| [getRangeStartIndex()](#getRangeStartIndex--) | 연속 유니코드 범위의 첫 번째 인덱스를 가져옵니다. |
| [getRangeEndIndex()](#getRangeEndIndex--) | 연속 유니코드 범위의 마지막 인덱스를 가져옵니다. |
| [getCount()](#getCount--) | 범위에 실제로 정의된 폰트 수를 가져옵니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 폰트 이름을 가져옵니다. |
| [clear()](#clear--) | 목록에서 모든 폰트를 제거합니다. |
| [remove(String fontName)](#remove-java.lang.String-) | 목록에서 특정 FallBack 폰트의 첫 번째 발생을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 목록에서 지정된 인덱스에 있는 FallBack 폰트를 제거합니다. |
| [toArray()](#toArray--) | 이 규칙에 대한 모든 FallBack 폰트를 포함하는 배열을 생성하고 반환합니다. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 목록의 지정된 범위에서 모든 FallBack 폰트를 포함하는 배열을 생성하고 반환합니다. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | 컬렉션에서 지정된 규칙의 인덱스를 반환합니다. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```


새 폰트(들)를 FallBack 폰트 목록에 추가합니다.

--------------------

> ```
> //새로운 FantFallBackRule 인스턴스를 생성합니다
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //규칙에 두 번째 폰트를 추가합니다 
>  newRule.addFallBackFonts("MS Gothic");
>  //규칙에 세 번째와 네 번째 폰트를 추가합니다 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | java.lang.String | FallBack용 폰트 이름 또는 이름(쉼표로 구분) |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```


새 폰트(들)를 FallBack 폰트 목록에 추가합니다.

--------------------

> ```
> //새로운 FontFallBackRule 인스턴스를 생성합니다
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //규칙에 다른 세 개의 폰트를 추가합니다
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontNames | java.lang.String[] | FallBack용 폰트 이름 또는 이름(쉼표로 구분) |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```


연속 유니코드 범위의 첫 번째 인덱스를 가져옵니다.

**반환값:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```


연속 유니코드 범위의 마지막 인덱스를 가져옵니다.

**반환값:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```


범위에 실제로 정의된 폰트 수를 가져옵니다.

**반환값:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```


지정된 인덱스에 있는 폰트 이름을 가져옵니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
java.lang.String
### clear() {#clear--}
```
public abstract void clear()
```


목록에서 모든 폰트를 제거합니다.

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```


목록에서 특정 FallBack 폰트의 첫 번째 발생을 제거합니다.

--------------------

> ```
> // 글꼴 목록을 포함하는 규칙을 생성합니다.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // 목록에서 Tahoma를 제거합니다
>  newRule.remove("Tahoma");
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | java.lang.String | 목록에서 제거할 폰트 이름입니다. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


목록에서 지정된 인덱스에 있는 FallBack 폰트를 제거합니다.

--------------------

> ```
> // 글꼴 목록을 포함하는 규칙을 생성합니다.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // 목록에서 Tahoma를 제거합니다
>  newRule.remove(2);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 제거할 폰트의 0 기반 인덱스입니다. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```


이 규칙에 대한 모든 FallBack 폰트를 포함하는 배열을 생성하고 반환합니다.

--------------------

> ```
> // 글꼴 목록을 포함하는 규칙을 생성합니다.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // 모든 폰트 이름을 배열로 가져옵니다
>  String[] fontNames = newRule.toArray();
> ```

**반환값:**
java.lang.String[] - String 배열
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```


목록의 지정된 범위에서 모든 FallBack 폰트를 포함하는 배열을 생성하고 반환합니다.

--------------------

> ```
> // 글꼴 목록을 포함하는 규칙을 생성합니다.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // 마지막 두 개의 폰트 이름을 배열로 가져옵니다
>  String[] fontNames = newRule.toArray(2,2);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startIndex | int | 추가할 첫 번째 폰트의 인덱스입니다. |
| count | int | 추가할 폰트 수입니다. |

**반환값:**
java.lang.String[] - String 배열
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```


컬렉션에서 지정된 규칙의 인덱스를 반환합니다.

--------------------

> ```
> // 글꼴 목록을 포함하는 규칙을 생성합니다.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Tahoma의 인덱스를 가져옵니다
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | java.lang.String | 찾을 폰트 이름입니다. |

**반환값:**
int - 폰트 인덱스 또는 목록에 폰트가 없으면 -1.