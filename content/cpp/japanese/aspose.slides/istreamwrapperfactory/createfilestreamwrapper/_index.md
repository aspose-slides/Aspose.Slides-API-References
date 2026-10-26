---
title: CreateFileStreamWrapper()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたパスと作成モードで FileStream を作成します。
type: docs
weight: 14
url: /ja/aspose.slides/istreamwrapperfactory/createfilestreamwrapper/
---
## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode) メソッド


指定されたパスと作成モードで FileStream を作成します。

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | ファイル名 [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | ファイルモード [System::IO::FileMode](../../../system.io/filemode/) |

### 戻り値

COM インターフェイス [IStreamWrapper](../../istreamwrapper/) のストリームラッパー

## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode, System::IO::FileAccess) メソッド


指定されたパス、作成モード、および読み書き権限で FileStream を作成します。

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode, System::IO::FileAccess fileAccess)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | ファイル名 [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | ファイルモード [System::IO::FileMode](../../../system.io/filemode/) |
| fileAccess | [System::IO::FileAccess](../../../system.io/fileaccess/) | ファイルアクセス [System::IO::FileAccess](../../../system.io/fileaccess/) |

### 戻り値

COM インターフェイス [IStreamWrapper](../../istreamwrapper/) のストリームラッパー

## 関連項目

* Enum [FileMode](../../../system.io/filemode/)
* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IStreamWrapper](../../istreamwrapper/)
* Class [String](../../../system/string/)
* Class [IStreamWrapperFactory](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)