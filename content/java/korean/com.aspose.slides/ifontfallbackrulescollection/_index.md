---
title: IFontFallBackRulesCollection
second_title: Aspose.Slides for Java API 레퍼런스
description: 사용자가 정의한 FontFallBack 규칙의 컬렉션을 나타냅니다
type: docs
url: /ko/com.aspose.slides/ifontfallbackrulescollection/
---
**구현된 모든 인터페이스:**
com.aspose.slides.IGenericCollection
```
public interface IFontFallBackRulesCollection extends IGenericCollection<IFontFallBackRule>
```

사용자가 정의한 FontFallBack 규칙의 컬렉션을 나타냅니다.
## Methods

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 규칙을 가져옵니다. |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | 새로운 FallBack 규칙을 컬렉션의 끝에 추가합니다. |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | 컬렉션에서 특정 FallBack 규칙의 첫 번째 항목을 제거합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IFontFallBackRule get_Item(int index)
```

지정된 인덱스에 있는 규칙을 가져옵니다. 읽기 전용 [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //FontsManager에서 비어 있거나 미리 초기화된 규칙 컬렉션 가져오기
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //컬렉션에 여러 규칙을 추가하기
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //컬렉션에서 첫 번째 규칙 객체를 가져오기
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

반환값:
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public abstract void add(IFontFallBackRule sourceRule)
```

새로운 FallBack 규칙을 컬렉션의 끝에 추가합니다.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //FontsManager에서 비어 있거나 사전 초기화된 규칙 컬렉션 가져오기
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //컬렉션에 새 규칙 추가하기
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | 추가할 지정된 규칙 |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public abstract void remove(IFontFallBackRule targetRule)
```

컬렉션에서 특정 FallBack 규칙의 첫 번째 항목을 제거합니다.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //FontsManager에서 비어 있거나 사전 초기화된 규칙 컬렉션 가져오기
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //컬렉션에 여러 규칙을 추가하기
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //컬렉션에서 첫 번째 규칙 객체를 가져오기
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>      //제거하기
>      rulesList.remove(firstRule);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | 컬렉션에서 제거할 규칙. |