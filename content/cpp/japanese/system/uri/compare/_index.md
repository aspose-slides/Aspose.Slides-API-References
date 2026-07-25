---
title: Compare()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された Uri オブジェクトを、指定された比較ルールで比較します。
type: docs
weight: 521
url: /ja/system/uri/compare/
---
## Uri::Compare(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, UriComponents, UriFormat, StringComparison) メソッド


指定された [Uri](../) オブジェクトを指定された比較ルールで比較します。

```cpp
static int32_t System::Uri::Compare(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2, UriComponents partsToCompare, UriFormat compareFormat, StringComparison comparisonType)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| uri1 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 最初の比較対象 |
| uri2 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 2番目の比較対象 |
| partsToCompare | [UriComponents](../../uricomponents/) | **uri1** と **uri2** の比較対象部分を指定します |
| compareFormat | [UriFormat](../../uriformat/) | URI のコンポーネントを比較する際に使用される文字エスケープ方法を指定します |
| comparisonType | [StringComparison](../../stringcomparison/) | StringComparison のいずれかの値 |

### 戻り値

**uri1** が **uri2** より小さい場合は負の値、等しい場合は 0、**uri1** が **uri2** より大きい場合は正の値が返されます

## 参照

* Enum [UriComponents](../../uricomponents/)
* Enum [UriFormat](../../uriformat/)
* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)