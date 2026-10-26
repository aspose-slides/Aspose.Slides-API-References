---
title: ResourceLoadingAction
second_title: Aspose.Slides for Java API リファレンス
description: 外部リソースの読み込みモードを指定します。
type: docs
url: /ja/com.aspose.slides/resourceloadingaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

外部リソースの読み込みモードを指定します。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [Default](#Default) | Aspose.Slides は外部リソースを通常どおりロードします。 |
| [Skip](#Skip) | Aspose.Slides は外部リソースのロードをスキップします。 |
| [UserProvided](#UserProvided) | Aspose.Slides は、ユーザーが[IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs#setData-byte---)で提供したバイト配列を画像データとして使用します。 |
### Default {#Default}
```
public static final int Default
```

Aspose.Slides は外部リソースを通常どおりロードします。

### Skip {#Skip}
```
public static final int Skip
```

Aspose.Slides は外部リソースのロードをスキップします。 データがないリンクのみが画像として保存されます。

### UserProvided {#UserProvided}
```
public static final int UserProvided
```

Aspose.Slides は、ユーザーが[IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs#setData-byte---)で提供したバイト配列を画像データとして使用します。