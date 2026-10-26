---
title: RequestCacheLevel
second_title: Aspose.Slides for C++ API リファレンス
description: この列挙体は、任意の WebRequest に適用できるキャッシュ設定を説明します。
type: docs
weight: 27
url: /ja/system.net.cache/requestcachelevel/
---
## RequestCacheLevel 列挙体

この列挙体は、任意の [WebRequest](../../system.net/webrequest/) に適用できるキャッシュ設定を説明します。

```cpp
enum class RequestCacheLevel
```

### 値

| Name | Value | Description |
| --- | --- | --- |
| Default | 0 | リソースへの要求は、リソースのキャッシュコピーを使用するか、サーバーへリクエストを送信することで満たされます。 |
| BypassCache | 1 | 要求はサーバーを使用して満たされます。キャッシュからエントリは取得されません。 |
| CacheOnly | 2 | リソースへの要求はキャッシュからのみ満たされます。クライアントキャッシュにリソースが存在しない場合、WebException がスローされます。 |
| CacheIfAvailable | 3 | リソースが利用可能な場合はキャッシュから要求を満たし、そうでない場合はサーバーにリクエストを送信します。 |
| Revalidate | 4 | クライアントのタイムスタンプがサーバー上のリソースのタイムスタンプと同じ場合はローカルコピーを使用します。そうでない場合はサーバーからリソースをダウンロードします。 |
| Reload | 5 | リソースは常にサーバーからダウンロードされます。 |
| NoCacheNoStore | 6 | キャッシュからリソースを使用して要求を満たすことはなく、リソースもキャッシュしません。 |

## 参照

* 名前空間 [System::Net::Cache](../)
* ライブラリ [Aspose.Slides](../../)