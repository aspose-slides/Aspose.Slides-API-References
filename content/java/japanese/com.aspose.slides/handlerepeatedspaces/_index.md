---
title: HandleRepeatedSpaces
second_title: Aspose.Slides for Java API リファレンス
description: Markdown エクスポート時に、連続した通常のスペース文字の処理方法を指定します。
type: docs
url: /ja/com.aspose.slides/handlerepeatedspaces/
---
**継承:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

Markdown エクスポート時に、連続した通常のスペース文字の処理方法を指定します。

## フィールド

| Field | Description |
| --- | --- |
| [None](#None) | すべてのスペースは変更せずに通常のスペース文字として保持されます。 |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | 2 つ以上連続する通常のスペース文字のシーケンスを、通常のスペース文字と非改行スペースエンティティ NBSP を交互に置き換えて変換します。 |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | 2 つ以上連続する通常のスペース文字のシーケンスを、最初のスペースを通常のスペース文字として保持し、以降のスペースをすべて非改行スペースエンティティ NBSP に置き換えて変換します。 |

### None {#None}
```
public static final int None
```

すべてのスペースは変更せずに通常のスペース文字として保持されます。変換は行われず、複数の連続スペースはそのままエクスポートされます。

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```

2 つ以上連続する通常のスペース文字のシーケンスを、通常のスペース文字と非改行スペースエンティティ NBSP を交互に置き換えて変換します。最初のスペースは常に通常のスペースとして保持されます。

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```

2 つ以上連続する通常のスペース文字のシーケンスを、最初のスペースを通常のスペース文字として保持し、以降のスペースをすべて非改行スペースエンティティ NBSP に置き換えて変換します。