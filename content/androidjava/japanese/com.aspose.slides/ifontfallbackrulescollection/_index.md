---
title: IFontFallBackRulesCollection
second_title: Aspose.Slides for Android via Java API リファレンス
description: ユーザーが定義した FontFallBack ルールのコレクションを表します
type: docs
url: /ja/com.aspose.slides/ifontfallbackrulescollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.slides.IGenericCollection
```
public interface IFontFallBackRulesCollection extends IGenericCollection<IFontFallBackRule>
```

ユーザーが定義した FontFallBack ルールのコレクションを表します
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスのルールを取得します。 |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | コレクションの末尾に新しい FallBack ルールを追加します。 |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | コレクションから特定の FallBack ルールの最初の出現を削除します。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IFontFallBackRule get_Item(int index)
```

指定されたインデックスのルールを取得します。読み取り専用 [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //FontsManager から空または事前初期化されたルールコレクションを取得
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //コレクションに複数のルールを追加
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //コレクション内の最初のルールのオブジェクトを取得
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int |  |

**戻り値:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public abstract void add(IFontFallBackRule sourceRule)
```

コレクションの末尾に新しい FallBack ルールを追加します。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //FontsManager から空または事前に初期化されたルールコレクションを取得
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //コレクションに新しいルールを追加
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | 追加するために指定されたルール |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public abstract void remove(IFontFallBackRule targetRule)
```

コレクションから特定の FallBack ルールの最初の出現を削除します。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //FontsManager から空または事前に初期化されたルールコレクションを取得
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //コレクションに複数のルールを追加
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //コレクション内の最初のルールのオブジェクトを取得
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>      //削除
>      rulesList.remove(firstRule);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | コレクションから削除するルール。