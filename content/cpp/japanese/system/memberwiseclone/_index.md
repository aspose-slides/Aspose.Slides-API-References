---
title: MemberwiseClone()
second_title: Aspose.Slides for C++ APIリファレンス
description: コピーコンストラクタを使用してメンバ単位のクローンを作成します。
type: docs
weight: 2601
url: /ja/system/memberwiseclone/
---
## System::MemberwiseClone(T *) 関数


コピーコンストラクタを使用してメンバ単位のクローンを作成します。

```cpp
template<typename T> SmartPtr<Object> System::MemberwiseClone(T *ptr)
```


### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| T | コピーコンストラクトされるクラス。サブクラス情報は失われます。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ptr | T * | クローン対象オブジェクトへのポインタ。 |

### 戻り値

クローンされたオブジェクトへのポインタ。

## 参照

* クラス [SmartPtr](../smartptr/)
* クラス [Object](../object/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)