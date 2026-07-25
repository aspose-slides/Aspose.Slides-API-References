---
title: GetFactory()
second_title: C++ 用 Aspose.Slides API リファレンス
description: 名前で DB プロバイダーのファクトリを取得します。
type: docs
weight: 1
url: /ja/system.data.common/dbproviderfactories/getfactory/
---
## DbProviderFactories::GetFactory(const String\&) メソッド

名前で DB プロバイダーのファクトリを取得します。

```cpp
static SharedPtr<DbProviderFactory> System::Data::Common::DbProviderFactories::GetFactory(const String &providerInvariantName)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| providerInvariantName | const [String](../../../system/string/)\& | プロバイダー名（例: データベースベンダー名）。 |

### 戻り値

プロバイダーのファクトリ。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [DbProviderFactory](../../dbproviderfactory/)
* クラス [String](../../../system/string/)
* クラス [DbProviderFactories](../)
* 名前空間 [System::Data::Common](../../)
* Library [Aspose.Slides](../../../)