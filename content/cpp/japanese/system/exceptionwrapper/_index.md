---
title: ExceptionWrapper
second_title: Aspose.Slides for C++ API リファレンス
description: Exception クラスから派生した例外のラッパーを表すテンプレートです。
type: docs
weight: 833
url: /ja/system/exceptionwrapper/
---
## ExceptionWrapper クラス

Exception クラスから派生した例外のラッパーを表すテンプレートです。

```cpp
template<typename T>class ExceptionWrapper
```

## メソッド

| メソッド | 説明 |
| --- | --- |
|  [ExceptionWrapper](./exceptionwrapper/)(std::nullptr_t) | [ExceptionWrapper](./) クラスの null インスタンスを構築し、例外を表しません。 |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionPtr](../exceptionptr/)\&) | [ExceptionWrapper](./) クラスのインスタンスを構築し、渡されたポインタを保持します。 |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionWrapper](./)\&) | コピーコンストラクタ。 |
|  [ExceptionWrapper](./exceptionwrapper/)([ExceptionWrapper](./)\&&) | ムーブコンストラクタ。 |
| explicit  [ExceptionWrapper](./exceptionwrapper/)(Args\&&...) | Exception クラスのコンストラクタへパラメータを転送し、新しい Exception クラスのインスタンスを保持するスマートポインタを作成するコンストラクタ。 |
| static void * [operator new](./operator_new/)(std::size_t) |  |
| static void * [operator new[]](./operator_new[]/)(std::size_t) |  |
|  [operator SharedPtr< Object >](./operator_sharedptr_less_object__greater/)() | SharedPtr<Object> への暗黙的なキャスト演算子。 |
| T * [operator->](./operator_minus_greater/)() const | Exception オブジェクトのメンバーにアクセスできるようにします。 |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)(const [ExceptionWrapper](./)\&) | 代入演算子。 |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)([ExceptionWrapper](./)\&&) | ムーブ代入演算子。 |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Exception 型の [System::TypeInfo](../typeinfo/) オブジェクトを取得するショートカット。 |

## 型エイリアス

| 型エイリアス | 説明 |
| --- | --- |
| [ExceptionType](./exceptiontype/) | キャスト関数で使用されます。 |

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)