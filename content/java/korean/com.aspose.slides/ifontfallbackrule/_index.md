---
title: IFontFallBackRule
second_title: Aspose.Slides for Java API 참조
description: 글꼴 대체 규칙을 나타냅니다
type: docs
url: /ko/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

글꼴 대체 규칙을 나타냅니다
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | 새 글꼴을 FallBack 글꼴 목록에 추가합니다. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | 새 글꼴을 FallBack 글꼴 목록에 추가합니다. |
| [getRangeStartIndex()](#getRangeStartIndex--) | 연속 유니코드 범위의 첫 번째 인덱스를 가져옵니다. |
| [getRangeEndIndex()](#getRangeEndIndex--) | 연속 유니코드 범위의 마지막 인덱스를 가져옵니다. |
| [getCount()](#getCount--) | 범위에 실제 정의된 글꼴 수를 가져옵니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 글꼴 이름을 가져옵니다. |
| [clear()](#clear--) | 목록에서 모든 글꼴을 제거합니다. |
| [remove(String fontName)](#remove-java.lang.String-) | 목록에서 특정 FallBack 글꼴의 첫 번째 항목을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 목록에서 지정된 인덱스에 있는 FallBack 글꼴을 제거합니다. |
| [toArray()](#toArray--) | 이 규칙에 대한 모든 FallBack 글꼴이 포함된 배열을 생성하고 반환합니다. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 목록에서 지정된 범위의 모든 FallBack 글꼴이 포함된 배열을 생성하고 반환합니다. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | 컬렉션에서 지정된 규칙의 인덱스를 반환합니다. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```

새 글꼴을 FallBack 글꼴 목록에 추가합니다.

--------------------

> ```
> //FantFallBackRule의 새 인스턴스를 생성합니다
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //규칙에 두 번째 글꼴을 추가합니다 
>  newRule.addFallBackFonts("MS Gothic");
>  //규칙에 세 번째와 네 번째 글꼴을 추가합니다 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | java.lang.String | FallBack용 쉼표로 구분된 글꼴 이름 또는 이름들 |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```

새 글꼴을 FallBack 글꼴 목록에 추가합니다.

--------------------

> ```
> //FontFallBackRule의 새 인스턴스를 생성합니다
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //규칙에 또 다른 세 개의 글꼴을 추가합니다 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontNames | java.lang.String[] | FallBack용 쉼표로 구분된 글꼴 이름 또는 이름들 |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```

연속 유니코드 범위의 첫 번째 인덱스를 가져옵니다.

**반환:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```

연속 유니코드 범위의 마지막 인덱스를 가져옵니다.

**반환:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```

범위에 실제 정의된 글꼴 수를 가져옵니다.

**반환:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```

지정된 인덱스의 글꼴 이름을 가져옵니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환:**
java.lang.String
### clear() {#clear--}
```
public abstract void clear()
```

목록에서 모든 글꼴을 제거합니다.

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```

목록에서 특정 FallBack 글꼴의 첫 번째 항목을 제거합니다.

--------------------

> ```
> // 글꼴 목록을 포함하는 규칙을 생성합니다.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // 리스트에서 Tahoma를 제거합니다
>  newRule.remove("Tahoma");
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | java.lang.String | 목록에서 제거할 글꼴 이름 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

목록에서 지정된 인덱스에 있는 FallBack 글꼴을 제거합니다.

--------------------

> ```
> // 글꼴 목록을 포함하는 규칙을 생성합니다.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //리스트에서 Tahoma를 제거합니다
>  newRule.remove(2);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 제거할 글꼴의 0부터 시작하는 인덱스 |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

이 규칙에 대한 모든 FallBack 글꼴이 포함된 배열을 생성하고 반환합니다.

--------------------

> ```
> // 글꼴 목록을 포함하는 규칙을 생성합니다.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // 모든 글꼴 이름을 배열로 가져옵니다
>  String[] fontNames = newRule.toArray();
> ```

**반환:**
java.lang.String[] - 문자열 배열
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```

목록에서 지정된 범위의 모든 FallBack 글꼴이 포함된 배열을 생성하고 반환합니다.

--------------------

> ```
> // 글꼴 목록을 포함하는 규칙을 생성합니다.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // 마지막 두 개의 글꼴 이름을 배열로 가져옵니다
>  String[] fontNames = newRule.toArray(2,2);
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startIndex | int | 추가할 첫 번째 글꼴의 인덱스 |
| count | int | 추가할 글꼴 수 |

**반환:**
java.lang.String[] - 문자열 배열
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```

컬렉션에서 지정된 규칙의 인덱스를 반환합니다.

--------------------

> ```
> // 글꼴 목록을 포함하는 규칙을 생성합니다.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Tahoma의 인덱스를 가져옵니다
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | java.lang.String | 찾을 글꼴 이름 |

**반환:**
int - 글꼴의 인덱스 또는 목록에 없을 경우 -1.