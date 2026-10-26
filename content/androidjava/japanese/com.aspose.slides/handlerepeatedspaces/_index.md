---
title: HandleRepeatedSpaces
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: Markdown エクスポート時に、連続する通常のスペース文字をどのように処理するかを指定します。
type: docs
url: /ja/com.aspose.slides/handlerepeatedspaces/
---
**継承:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

Markdown エクスポート時に、連続する通常のスペース文字をどのように処理するかを指定します。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [None](#None) | すべてのスペースが変更されずに通常のスペース文字として保持されます。 |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | 2 つ以上連続する通常のスペースのシーケンスを、通常のスペース文字とノーブレークスペースエンティティ NBSP を交互に置き換えて変換します。 |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | 2 つ以上連続する通常のスペースのシーケンスを、最初のスペースを通常のスペース文字として保持し、以降のすべてのスペースをノーブレークスペースエンティティ NBSP に置き換えて変換します。 |
### None {#None}
```
public static final int None
```

すべてのスペースが変更されずに通常のスペース文字として保持されます。変換は適用されず、複数の連続スペースはそのままエクスポートされます。

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```

2 つ以上連続する通常のスペースのシーケンスを、通常のスペース文字とノーブレークスペースエンティティ NBSP を交互に置き換えて変換します。最初のスペースは常に通常のスペースとして保持されます。

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```

2 つ以上連続する通常のスペースのシーケンスを、最初のスペースを通常のスペース文字として保持し、以降のすべてのスペースをノーブレークスペースエンティティ NBSP に置き換えて変換します。