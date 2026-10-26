---
title: HttpCacheAgeControl
second_title: Aspose.Slides for C++ API リファレンス
description: CacheAgeControl は、キャッシュされた項目の有効期限と鮮度に関する設定を指定するために使用されます。
type: docs
weight: 53
url: /ja/system.net.cache/httpcacheagecontrol/
---
## HttpCacheAgeControl 列挙型

CacheAgeControl は、キャッシュされた項目の有効期限と鮮度に関する設定を指定するために使用されます。

```cpp
enum class HttpCacheAgeControl
```

### 列挙値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | 0 | 内部使用のみ。 |
| MinFresh | 1 | 有効期限までの残り時間がこの値で指定された時間以上である場合、キャッシュからコンテンツを取得できます。 |
| MaxAge | 2 | この値で指定された期間より古くなるまで、キャッシュからコンテンツを取得できます。 |
| MaxStale | 4 | 有効期限が切れた後でも、この値で指定された時間が経過するまでキャッシュからコンテンツを取得できます。 |
| MaxAgeAndMinFresh | 3 | MaxAge と MinFresh。 |
| MaxAgeAndMaxStale | 6 | MaxAge と MaxStale。 |

## 参照

* 名前空間 [System::Net::Cache](../)
* ライブラリ [Aspose.Slides](../../)