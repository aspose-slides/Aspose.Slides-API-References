---
title: Is()
second_title: Aspose.Slides for C++ API リファレンス
description: ポインタが指すオブジェクトが特定の型またはその子孫型かどうかをチェックします。C# の 'is' セマンティクスに従います。
type: docs
weight: 300
url: /ja/system/smartptr/is/
---
## SmartPtr::Is(const System::TypeInfo\&) const メソッド

ポインタが指すオブジェクトが特定の型またはその子孫型かどうかを確認します。C# の 'is' セマンティクスに従います。

```cpp
bool System::SmartPtr<T>::Is(const System::TypeInfo &target) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | チェック対象となるターゲット型を指定します。 |

### 戻り値

C# の 'is' スタイルのチェックが true の場合は true、そうでない場合は false を返します。

## 備考

実装。

## 関連項目

* クラス [TypeInfo](../../typeinfo/)
* クラス [SmartPtr](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)