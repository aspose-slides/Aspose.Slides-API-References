---
title: LinkEmbedDecision
second_title: Aspose.Slides for Android の Java API リファレンス
description: 保存時にオブジェクトがどのように処理されるかを決定します。
type: docs
url: /ja/com.aspose.slides/linkembeddecision/
---
**継承:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

オブジェクトが保存時にどのように処理されるかを決定します。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [Link](#Link) | オブジェクトは外部に保存され、URLで参照されます |
| [Embed](#Embed) | 可能であれば、オブジェクトは生成されたファイルに埋め込まれるべきです。 |
| [Ignore](#Ignore) | オブジェクトは無視されます。 |
### リンク {#Link}
```
public static final int Link
```


オブジェクトは外部に保存され、URLで参照されます

### 埋め込み {#Embed}
```
public static final int Embed
```


オブジェクトは可能であれば生成されたファイルに埋め込まれるべきです。埋め込みが不可能な場合、GetUrl が呼び出され、結果に応じてオブジェクトは URL で参照されるか、無視されます。

### 無視 {#Ignore}
```
public static final int Ignore
```


オブジェクトは無視されます