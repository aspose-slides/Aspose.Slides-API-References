---
title: IBehaviorProperty
second_title: Aspose.Slides for Android via Java API Reference
description: Represent property types for animation behavior.
type: docs
url: /ja/com.aspose.slides/ibehaviorproperty/
---```
public interface IBehaviorProperty
```

アニメーション動作のプロパティタイプを表します。プロパティの一覧は https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx と https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx に従います。

## メソッド

| Method | Description |
| --- | --- |
| [getValue()](#getValue--) | Value of the property |
| [isCustom()](#isCustom--) | Shows if this property does not belong to the predefined properties list in the specification: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |

### getValue() {#getValue--}
```
public abstract String getValue()
```

プロパティの値

**戻り値:**  
java.lang.String

### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```

このプロパティが仕様の定義済みプロパティ一覧に含まれていないかどうかを示します: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**戻り値:**  
boolean