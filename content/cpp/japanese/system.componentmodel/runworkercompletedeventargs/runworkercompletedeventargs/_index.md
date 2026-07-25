---
title: RunWorkerCompletedEventArgs()
second_title: Aspose.Slides for C++ APIリファレンス
description: コンストラクタ。
type: docs
weight: 1
url: /ja/system.componentmodel/runworkercompletedeventargs/runworkercompletedeventargs/
---
## RunWorkerCompletedEventArgs::RunWorkerCompletedEventArgs(const System::SharedPtr\<System::Object\>\&, const System::Exception\&, bool) コンストラクタ

コンストラクタ。

```cpp
System::ComponentModel::RunWorkerCompletedEventArgs::RunWorkerCompletedEventArgs(const System::SharedPtr<System::Object> &result, const System::Exception &error, bool canceled)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| result | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | 非同期操作の結果。 |
| error | const [System::Exception](../../../system/exception/)\& | 非同期操作中に発生したエラー。 |
| canceled | **bool** | 非同期操作がキャンセルされたかどうかを示す値。 |

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [Exception](../../../system/exception/)
* クラス [Object](../../../system/object/)
* クラス [RunWorkerCompletedEventArgs](../)
* 名前空間 [System::ComponentModel](../../)
* ライブラリ [Aspose.Slides](../../../)