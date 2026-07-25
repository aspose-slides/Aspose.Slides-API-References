---
title: CreateFileStreamWrapper()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたパスと作成モードで FileStream を作成します。
type: docs
weight: 14
url: /ja/aspose.slides/streamwrapperfactory/createfilestreamwrapper/
---
## StreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode) メソッド

指定されたパスと作成モードで FileStream を作成します。

```cpp
System::SharedPtr<IStreamWrapper> Aspose::Slides::StreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode) override
```

## StreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode, System::IO::FileAccess) メソッド

指定されたパス、作成モード、および読み取り/書き込み権限で FileStream を作成します。

```cpp
System::SharedPtr<IStreamWrapper> Aspose::Slides::StreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode, System::IO::FileAccess fileAccess) override
```

## 参照

* 列挙型 [FileMode](../../../system.io/filemode/)
* 列挙型 [FileAccess](../../../system.io/fileaccess/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IStreamWrapper](../../istreamwrapper/)
* クラス [String](../../../system/string/)
* クラス [StreamWrapperFactory](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)