---
title: OperatingSystem
second_title: "Aspose.Slides for C++ APIリファレンス"
description: "特定のオペレーティングシステムを表し、その情報を提供します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使ってこの型のインスタンスを作成しないでください。そうしないと実行時エラーやアサーション違反が発生します。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数への引数として使用してください。"
type: docs
weight: 1171
url: /ja/system/operatingsystem/
---

## OperatingSystem クラス

特定のオペレーティングシステムを表し、その情報を提供します。このクラスのオブジェクトは [System::MakeObject()](../makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使ってこの型のインスタンスを作成しないでください。そうしないと実行時エラーやアサーション違反が発生します。このクラスは常に [System::SmartPtr](../smartptr/) ポインタでラップし、そのポインタを関数への引数として使用してください。

```cpp
class OperatingSystem
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [PlatformID](../platformid/) [get_Platform](./get_platform/)() const | 現在のオブジェクトが表すオペレーティングシステムのプラットフォーム識別子を返します。 |
| [String](../string/) [get_ServicePack](./get_servicepack/)() const | 現在のオブジェクトが表すオペレーティングシステムのサービスパック名を返します。 |
| const [Version](../version/)\& [get_Version](./get_version/)() const | 現在のオブジェクトが表すオペレーティングシステムのバージョンを表す [Version](../version/) オブジェクトへの定数参照を返します。 |
| [String](../string/) [get_VersionString](./get_versionstring/)() const | 現在のオブジェクトが表すオペレーティングシステムのバージョンの文字列表現を返します。 |
| static **bool** [IsFreeBSD](./isfreebsd/)() | 現在のアプリケーションが FreeBSD 上で実行されているかどうかを示します。 |
| static **bool** [IsLinux](./islinux/)() | 現在のアプリケーションが Linux 上で実行されているかどうかを示します。 |
| static **bool** [IsMacOS](./ismacos/)() | 現在のアプリケーションが MacOS 上で実行されているかどうかを示します。 |
| static **bool** [IsOSPlatform](./isosplatform/)(const [String](../string/)\&) | 現在のアプリケーションが指定されたプラットフォーム上で実行されているかどうかを示します。 |
| static **bool** [IsWindows](./iswindows/)() | 現在のアプリケーションが [Windows](../../system.windows/) 上で実行されているかどうかを示します。 |
| [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&) | 特定のプラットフォーム ID とバージョンとして指定されたオペレーティングシステムを表すインスタンスを構築します。 |
| [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&, const [String](../string/)\&) | 特定のプラットフォーム ID、バージョン、およびサービスパックとして指定されたオペレーティングシステムを表すインスタンスを構築します。 |
| [String](../string/) [ToString](./tostring/)() const | 現在のオブジェクトが表すオペレーティングシステムのバージョンの文字列表現を返します。 |

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)