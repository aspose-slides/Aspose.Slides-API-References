---
title: Version()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたメジャー、マイナー、ビルド、リビジョンの値を表すインスタンスを構築します。
type: docs
weight: 1
url: /ja/system/version/version/
---
## Version::Version(int, int, int, int) コンストラクタ

指定されたメジャー、マイナー、ビルド、およびリビジョンの値を表すインスタンスを構築します。

```cpp
System::Version::Version(int major, int minor, int build, int revision)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| major | int | The major version number |
| minor | int | The minor version numebr |
| build | int | The build number |
| revision | int | The revision number |

## Version::Version(int, int, int) コンストラクタ

指定されたメジャー、マイナー、ビルドの値を表すインスタンスを構築します。

```cpp
System::Version::Version(int major, int minor, int build)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| major | int | The major version number |
| minor | int | The minor version numebr |
| build | int | The build number |

## Version::Version(int, int) コンストラクタ

指定されたメジャーと値を表すインスタンスを構築します。

```cpp
System::Version::Version(int major, int minor)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| major | int | The major version number |
| minor | int | The minor version numebr |

## Version::Version(const String\&) コンストラクタ

文字列として表されるバージョン番号を表すインスタンスを構築します。

```cpp
System::Version::Version(const String &version)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| version | const [String](../../string/)\& | The string containing a version number |

## Version::Version() コンストラクタ

バージョン番号 0.0.-1.-1 を表すインスタンスを構築します。

```cpp
System::Version::Version()
```

## 参照

* クラス [Version](../)
* クラス [String](../../string/)
* 名前空間 [System](../../)
* Library [Aspose.Slides](../../../)