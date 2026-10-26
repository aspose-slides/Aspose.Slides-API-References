---
title: CultureTypes
second_title: Aspose.Slides for C++ API リファレンス
description: Culture カテゴリのビットマスクエントリ。
type: docs
weight: 443
url: /ja/system.globalization/culturetypes/
---
## CultureTypes 列挙体

Culture カテゴリのビットマスクエントリ。

```cpp
enum class CultureTypes : int32_t
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| NeutralCultures | 1 | 言語には特化しているが、国や地域には特化していない Culture。 |
| SpecificCultures | 2 | 国や地域に特化した SpecificCultures。 |
| InstalledWin32Cultures | 4 | OS にインストールされている Cultures。 |
| AllCultures | n/a | すべての利用可能なカルチャー。 |
| UserCustomCulture | 8 | ユーザー定義の cultures。 |
| ReplacementCultures | 16 | 既存の cultures に対するユーザー定義の置き換え。 |
| WindowsOnlyCultures | 32 | 非推奨。 |
| FrameworkCultures | 64 | 非推奨。 |

## 参照

* Namespace [System::Globalization](../)
* Library [Aspose.Slides](../../)