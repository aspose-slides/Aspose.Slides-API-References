---
title: HttpRequestCacheLevel
second_title: Aspose.Slides for C++ API リファレンス
description: この列挙型は HTTP のキャッシュ設定を説明します。
type: docs
weight: 40
url: /ja/system.net.cache/httprequestcachelevel/
---
## HttpRequestCacheLevel 列挙型

The enum describes cache settings for HTTP.

```cpp
enum class HttpRequestCacheLevel
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Default | 0 | リソースへの要求を、リソースのキャッシュされたコピーを使用するか、サーバーにリクエストを送信して満たします。 |
| BypassCache | 1 | サーバーを使用して要求を満たします。 |
| CacheOnly | 2 | 常にクライアントキャッシュを使用してリソースを取得します。 |
| CacheIfAvailable | 3 | リソースがキャッシュに存在すればキャッシュから要求を満たし、存在しない場合はサーバーにリクエストを送信します。 |
| Revalidate | 4 | クライアントのタイムスタンプがサーバー上のリソースのタイムスタンプと同じ場合はローカルコピーを使用します。そうでない場合はサーバーからリソースをダウンロードします。 |
| Reload | 5 | リソースは常にサーバーからダウンロードされます。 |
| NoCacheNoStore | 6 | キャッシュからリソースを使用して要求を満たすことはなく、リソースもキャッシュしません。 |
| CacheOrNextCacheOnly | 7 | ローカルコンピュータのキャッシュまたは LAN 上のリモートキャッシュのいずれかからリソースの要求を満たします。 |
| Refresh | 8 | サーバーまたはローカルキャッシュ以外のキャッシュを使用して要求を満たします。 |

## 参照

* 名前空間 [System::Net::Cache](../)
* ライブラリ [Aspose.Slides](../../)