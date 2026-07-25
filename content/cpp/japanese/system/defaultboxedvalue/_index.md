---
title: DefaultBoxedValue
second_title: Aspose.Slides for C++ API リファレンス
description: "BoxedValue クラスの実装です。共通コードを重複させずに BoxingValue の特殊化を宣言できるようにします。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使ってこの型のインスタンスを作成しないでください。そうしないと実行時エラーやアサーション違反が発生します。常にこのクラスを System::SmartPtr ポインタでラップし、そのポインタを関数の引数として渡してください。"
type: docs
weight: 274
url: /ja/system/defaultboxedvalue/
---
## DefaultBoxedValue クラス


[BoxedValue](../boxedvalue/) クラス実装。共通コードを重複させずに BoxingValue の特殊化を宣言できるようにします。 このクラスのオブジェクトは [System::MakeObject()](../makeobject/) 関数を使用してのみ割り当てるべきです。 スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないと実行時エラーやアサーション違反が発生します。 常にこのクラスを [System::SmartPtr](../smartptr/) ポインタでラップし、そのポインタを関数の引数として渡してください。

```cpp
template<class T>class DefaultBoxedValue : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
|  [DefaultBoxedValue](./defaultboxedvalue/)(const T\&) | 指定された値を表す [DefaultBoxedValue](./) クラスの新しいインスタンスを構築します。 |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | 現在のオブジェクトと指定されたオブジェクトが表すボックス化された値の等価性を判定します。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | 参照型オブジェクトを C# スタイルで比較します。 |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、ここでは 2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、ここでは 2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| int [GetHashCode](./gethashcode/)() const override | 現在のオブジェクトのハッシュコードを返します。 |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | オブジェクトの実際の型を取得します。 |
| **bool** [is](./is/)() const | 現在のオブジェクトが表すボックス化された値の型が **V** であるかどうかを判定します。 |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | オブジェクトが targetType で説明される型のインスタンスを表すかどうかを確認します。C# の 'is' 演算子に相当します。 |
| void [Lock](../object/lock/)() | C# の lock() 文のロック機能を実装します。直接呼び出すか、[LockContext](../lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../object/memberwiseclone/) メソッドに相当します。カスタム型のクローン作成を可能にします。 |
|  [Object](../object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../object/object/)([Object](../object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を weak ポインタ（shared ではなく）に設定します。コンテナ内のポインタを weak モードに切り替えることができます。 |
| int [SharedCount](../object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| [String](../string/) [ToString](./tostring/)() const override | ボックス化された値の文字列表現を返します。 |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# の typeof([System.Object](../object/)) 構文を実装します。 |
| const T\& [unbox](./unbox/)() const | ボックス化された値をアンボックスします。 |
| void [Unlock](../object/unlock/)() | C# の lock() 文のアンロック機能を実装します。直接呼び出すか、[LockContext](../lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | weak 参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | weak 参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参考

* クラス [Object](../object/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)