---
title: ResourceLoadingAction
second_title: Aspose.Slides の C++ API リファレンス
description: 外部リソースの読み込みモードを指定します。
type: docs
weight: 6761
url: /ja/aspose.slides/resourceloadingaction/
---
## ResourceLoadingAction 列挙型


外部リソースの読み込みモードを指定します。

```cpp
enum class ResourceLoadingAction
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Default | 0 | [Aspose.Slides](../) は通常どおり外部リソースを読み込みます。 |
| Skip | 1 | [Aspose.Slides](../) は外部リソースの読み込みをスキップします。画像の場合、データのないリンクのみが保存されます。 |
| UserProvided | 2 | [Aspose.Slides](../) は [IResourceLoadingArgs::SetData](../iresourceloadingargs/setdata/) でユーザーが提供したバイト配列を画像データとして使用します。 |

## 参照

* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)