---
title: FontFallBackRulesCollection
second_title: Aspose.Slides for Java API 참조
description: 사용자가 정의한 FontFallBack 규칙의 컬렉션을 나타냅니다
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

사용자가 정의한 FontFallBack 규칙의 컬렉션을 나타냅니다.
## 생성자

| Constructor | Description |
| --- | --- |
| [FontFallBackRulesCollection()](#FontFallBackRulesCollection--) |  |
## 메서드

| Method | Description |
| --- | --- |
| [size()](#size--) | 컬렉션에 실제로 포함된 규칙 수를 가져옵니다. |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | 지정된 FallBack 규칙을 컬렉션 끝에 추가합니다. |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | 컬렉션에서 특정 FallBack 규칙의 첫 번째 항목을 제거합니다. |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 규칙을 가져옵니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java 반복자를 반환합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 컬렉션의 모든 요소를 지정된 배열로 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 액세스가 동기화되어 있는지 여부를 나타내는 값을 반환합니다 (thread-safe). |
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

**Returns:**
int
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public final void add(IFontFallBackRule sourceRule)
```


지정된 FallBack 규칙을 컬렉션 끝에 추가합니다.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //FontsManager에서 비어 있거나 사전 초기화된 규칙 컬렉션 가져오기
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //컬렉션에 새 규칙 추가
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | 추가할 규칙 |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public final void remove(IFontFallBackRule targetRule)
```


컬렉션에서 특정 FallBack 규칙의 첫 번째 항목을 제거합니다.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //FontsManager에서 비어 있거나 사전 초기화된 규칙 컬렉션 가져오기
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //컬렉션에 여러 규칙 추가
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //컬렉션에서 첫 번째 규칙 객체 가져오기
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>      //제거
>      rulesList.remove(firstRule);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | 컬렉션에서 제거할 규칙. |

### get_Item(int index) {#get-Item-int-}
```
public final IFontFallBackRule get_Item(int index)
```


지정된 인덱스에 있는 규칙을 가져옵니다. 읽기 전용 [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //FontsManager에서 비어 있거나 사전 초기화된 규칙 컬렉션 가져오기
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //컬렉션에 여러 규칙 추가
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //컬렉션에서 첫 번째 규칙 객체 가져오기
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iterator()
```


컬렉션을 순회하는 열거자를 반환합니다.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - 컬렉션을 순회하는 데 사용할 수 있는 IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iteratorJava()
```


전체 컬렉션에 대한 java 반복자를 반환합니다.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - 전체 컬렉션에 대한 java.util.Iterator.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


컬렉션의 모든 요소를 지정된 배열로 복사합니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 대상 배열. |
| index | int | 대상 배열에서 시작 인덱스. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


컬렉션에 대한 액세스가 동기화되어 있는지 여부를 나타내는 값을 반환합니다 (thread-safe). 읽기 전용 boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


동기화 루트를 반환합니다. 읽기 전용 Object.

**Returns:**
java.lang.Object