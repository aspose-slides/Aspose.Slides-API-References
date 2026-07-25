---
title: OperatingSystem()
second_title: C++ 用 Aspose.Slides APIリファレンス
description: 特定のプラットフォーム ID とバージョンで指定されたオペレーティングシステムを表すインスタンスを構築します。
type: docs
weight: 1
url: /ja/system/operatingsystem/operatingsystem/
---
## OperatingSystem::OperatingSystem(PlatformID, const Version\&) コンストラクタ

特定のプラットフォーム ID とバージョンで指定されたオペレーティングシステムを表すインスタンスを構築します。

```cpp
System::OperatingSystem::OperatingSystem(PlatformID platform, const Version &version)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| platform | [PlatformID](../../platformid/) | 構築中のオブジェクトが表すオペレーティングシステムのプラットフォーム識別子 |
| version | const [Version](../../version/)\& | 構築中のオブジェクトが表すオペレーティングシステムのバージョン |

## OperatingSystem::OperatingSystem(PlatformID, const Version\&, const String\&) コンストラクタ

特定のプラットフォーム ID、バージョン、サービスパックで指定されたオペレーティングシステムを表すインスタンスを構築します。

```cpp
System::OperatingSystem::OperatingSystem(PlatformID platform, const Version &version, const String &service_pack)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| platform | [PlatformID](../../platformid/) | 構築中のオブジェクトが表すオペレーティングシステムのプラットフォーム識別子 |
| version | const [Version](../../version/)\& | 構築中のオブジェクトが表すオペレーティングシステムのバージョン |
| service_pack | const [String](../../string/)\& | 構築中のオブジェクトが表すオペレーティングシステムのサービスパックの名前 |

## 参照

* 列挙体 [PlatformID](../../platformid/)
* クラス [Version](../../version/)
* クラス [OperatingSystem](../)
* クラス [String](../../string/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)