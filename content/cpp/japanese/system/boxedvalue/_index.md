---
title: BoxedValue
second_title: Aspose.Slides for C++ API リファレンス
description: "ボックス化された値を表します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないと実行時エラーやアサーション違反が発生します。常にこのクラスを System::SmartPtr ポインタでラップし、そのポインタを関数への引数として使用してください。"
type: docs
weight: 105
url: /ja/system/boxedvalue/
---
## BoxedValue クラス

ボックス化された値を表します。このクラスのオブジェクトは [System::MakeObject()](../makeobject/) 関数を使用してのみ割り当てるべきです。この型のインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないと実行時エラーやアサーション違反が発生します。常にこのクラスを [System::SmartPtr](../smartptr/) ポインタでラップし、そのポインタを関数への引数として使用してください。

```cpp
template<class T>class BoxedValue : public System::BoxedValueBase,
                                    public std::conditional_t<BoxedValueDetail::ImplementsInterface_v<T, IComparable<T>>, BoxedValueDetail::Comparable<T, BoxedValue<T>>, BoxedValueDetail::NonComparable>
```

### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | クラスが表すボックス化された値の型 |

## メソッド

| Method | Description |
| --- | --- |
|   [BoxedValue](./boxedvalue/)(const T\&) | 指定されたボックス化された値を表すオブジェクトを構築します。 |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | 現在のオブジェクトと指定されたオブジェクトが表すボックス化された値の等価性を判定します。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等価ではありませんが、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等価ではありませんが、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| int [GetHashCode](./gethashcode/)() const override | 現在のオブジェクトのハッシュコードを返します。 |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | オブジェクトの実際の型を取得します。 |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const override | 現在のオブジェクトが表すボックス化された値の型を表す値を返します。 |
| **uint64_t** [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const override | キャスト可能な場合はボックス化されたオブジェクトの数値を返し、そうでなければ 0 を返します。 |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスを表すか確認します。C# の 'is' 演算子に相当します。 |
| **bool** [is](./is/)() const | 現在のオブジェクトが表すボックス化された値の型が **V** であるかを判定します。 |
| **bool** [IsBoxedEnum](./isboxedenum/)() override | 現在のオブジェクトが enum 型のボックス化された値を表すか判定します。 |
| void [Lock](../object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../lockcontext/) センティリーオブジェクトを使用してください。 |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../object/memberwiseclone/) メソッドに相当します。カスタム型のクローン作成を可能にします。 |
|   [Object](../object/object/)() | オブジェクトを作成し、すべての内部データ構造を初期化します。 |
|   [Object](../object/object/)([Object](../object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | 指定された列挙型の指定された名前の列挙定数の値をボックス化します。パラメータは列挙定数名を表す文字列を解釈する際に大文字小文字を無視するかどうかを指定します。 |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&) | 指定された列挙型の指定された名前の列挙定数の値をボックス化します。 |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | nullptr と値型オブジェクトを参照比較します。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | 共有参照カウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | 共有参照カウントを減少させて返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| [String](../string/) [ToString](./tostring/)() const override | 現在のオブジェクトが表すボックス化された値を文字列に変換します。 |
| [System::String](../string/) [ToString](../boxedvaluebase/tostring/)(const [System::String](../string/)\&) const | 指定された書式文字列を使用してボックス化されたオブジェクトを文字列に変換します。 |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# の typeof([System.Object](../object/)) 構文を実装します。 |
| const T\& [unbox](./unbox/)() const | 現在のオブジェクトが表す値のボックスを解除します。 |
| void [Unlock](../object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../lockcontext/) センティリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | 弱参照カウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../object/weakrefremoved/)() | 弱参照カウントを減少させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../object/~object/)() | オブジェクトを破棄し、すべての内部データ構造を解放します。 |

## 参照

* クラス [BoxedValueBase](../boxedvaluebase/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)