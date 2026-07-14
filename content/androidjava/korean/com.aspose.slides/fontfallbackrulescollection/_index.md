---
title: FontFallBackRulesCollection
second_title: Java API를 통한 Android용 Aspose.Slides 레퍼런스
description: 사용자가 정의한 FontFallBack 규칙 컬렉션을 나타냅니다
type: docs
url: /ko/com.aspose.slides/fontfallbackrulescollection/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
```
public class FontFallBackRulesCollection implements IFontFallBackRulesCollection
```

사용자에 의해 정의된 FontFallBack 규칙 컬렉션을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FontFallBackRulesCollection()](#FontFallBackRulesCollection--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [size()](#size--) | 컬렉션에 실제로 포함된 규칙 수를 가져옵니다. |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | 지정된 FallBack 규칙을 컬렉션의 끝에 추가합니다. |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | 컬렉션에서 특정 FallBack 규칙의 첫 번째 발생을 제거합니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 규칙을 가져옵니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java iterator를 반환합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 접근이 동기화(스레드 안전)되어 있는지 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |
### FontFallBackRulesCollection() {#FontFallBackRulesCollection--}
```
public FontFallBackRulesCollection()
```


### size() {#size--}
```
public final int size()
```


컬렉션에 실제로 포함된 규칙 수를 가져옵니다. 읽기 전용 int.

**반환값:**
int
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public final void add(IFontFallBackRule sourceRule)
```


지정된 FallBack 규칙을 컬렉션의 끝에 추가합니다.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //FontsManager에서 빈 또는 미리 초기화된 규칙 컬렉션을 가져옵니다
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //새 규칙을 컬렉션에 추가합니다
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | 추가하기 위한 지정된 규칙 |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public final void remove(IFontFallBackRule targetRule)
```


컬렉션에서 특정 FallBack 규칙의 첫 번째 발생을 제거합니다.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //FontsManager에서 빈 또는 미리 초기화된 규칙 컬렉션을 가져옵니다
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //컬렉션에 여러 규칙을 추가합니다
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //컬렉션에서 첫 번째 규칙 객체를 가져옵니다
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>      //제거합니다 
>      rulesList.remove(firstRule);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | 컬렉션에서 제거할 규칙 |

### get_Item(int index) {#get-Item-int-}
```
public final IFontFallBackRule get_Item(int index)
```


지정된 인덱스의 규칙을 가져옵니다. 읽기 전용 [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //FontsManager에서 빈 또는 미리 초기화된 규칙 컬렉션을 가져옵니다
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //컬렉션에 여러 규칙을 추가합니다
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //컬렉션에서 첫 번째 규칙 객체를 가져옵니다
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iterator()
```


컬렉션을 순회하는 열거자를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - 컬렉션을 순회하는 데 사용할 수 있는 IGenericEnumerator입니다.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iteratorJava()
```


전체 컬렉션에 대한 java iterator를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - 전체 컬렉션에 대한 java.util.Iterator입니다.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


컬렉션의 모든 요소를 지정된 배열에 복사합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 대상 배열. |
| index | int | 대상 배열에서 시작 인덱스. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


컬렉션에 대한 접근이 동기화(스레드 안전)되어 있는지 여부를 나타내는 값을 반환합니다. 읽기 전용 boolean.

**반환값:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


동기화 루트를 반환합니다. 읽기 전용 Object.

**반환값:**
java.lang.Object