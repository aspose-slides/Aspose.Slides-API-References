---
title: UriComponents
second_title: Aspose.Slides for C++ API リファレンス
description: URI コンポーネントを表します。
type: docs
weight: 3251
url: /ja/system/uricomponents/
---
## UriComponents 列挙型

URI コンポーネントを表します。

```cpp
enum class UriComponents
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Scheme | 1 | Scheme データ。 |
| UserInfo | 2 | UserInfo データ。 |
| Host | 4 | Host データ。 |
| Port | 8 | Port データ。 |
| SchemeAndServer | n/a | Scheme、Host、Port データ。 |
| Path | 16 | LocalPath データ。 |
| Query | 32 | Query データ。 |
| PathAndQuery | n/a | LocalPath と Query データ。 |
| HttpRequestUrl | n/a | Scheme、Host、Port、Query、LocalPath データ。 |
| Fragment | 64 | Fragment データ。 |
| AbsoluteUri | n/a | Scheme、Host、Port、Quer、LocalPath、Fragment データ。 |
| StrongPort | 128 | Port データ; ポート データが [Uri](../uri/) に存在しない場合で、Scheme にデフォルト ポートが割り当てられている場合はデフォルト ポートが返されます; デフォルト ポートが存在しない場合は -1 が返されます。 |
| HostAndPort | n/a | Host と Port データ; ポート データが [Uri](../uri/) に存在しない場合で、Scheme にデフォルト ポートが割り当てられている場合はデフォルト ポートが返されます。デフォルト ポートが存在しない場合は -1 が返されます。 |
| StrongAuthority | n/a | UserInfo、Host、Port データ.If ポート データが [Uri](../uri/) に存在しない場合で、Scheme にデフォルト ポートが割り当てられている場合はデフォルト ポートが返されます。デフォルト ポートが存在しない場合は -1 が返されます。 |
| NormalizedHost | 256 |  |
| KeepDelimiter | 1073741824 | 区切り文字を含めることを指定します。 |
| SerializationInfoString | n/a | [Uri](../uri/) コンテキスト全体は [Uri](../uri/) シリアライザに必要です。コンテキストには IPv6 スコープが含まれます。 |

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)