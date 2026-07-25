---
title: Object
second_title: Aspose.Slides for C++ API リファレンス
description: C# の System.Object クラスで利用できるメソッドを使用可能にする基底クラスです。翻訳環境で使用されるすべての非自明なクラスはこれを継承すべきです。
type: docs
weight: 1132
url: /ja/system/object/
---
## オブジェクト クラス


C# の [System.Object](./) クラスで利用可能なメソッドを使用できるようにする基底クラスです。翻訳された環境で使用されるすべての非自明なクラスはこれを継承すべきです。

```cpp
class Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](./equals/)([ptr](./ptr/)) | C# の [Object.Equals](./equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](./equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](./equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](./fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| Detail::SmartPtrCounter * [GetCounter](./getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](./gethashcode/)() const | C# の [Object.GetHashCode()](./gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](./gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](./is/)(const [TypeInfo](../typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](./lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../lockcontext/) センティリオブジェクトを使用してください。 |
| virtual [ptr](./ptr/) [MemberwiseClone](./memberwiseclone/)() const | C# の [Object.MemberwiseClone()](./memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](./object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](./object/)([Object](./) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](./)\& [operator=](./operator_equal/)([Object](./) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](./referenceequals/)([ptr](./ptr/) const\&, [ptr](./ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](./referenceequals/) の文字列と nullptr のケースに対する特化です。 |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](./referenceequals/) の文字列ケースに対する特化です。 |
| int [RemovedSharedRefs](./removedsharedrefs/)(int) | 指定された値だけ共有参照カウンタを減少させます。 |
| virtual void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](./sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](./) * [SharedRefAdded](./sharedrefadded/)() | 共有参照カウンタをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](./sharedrefremovedsafe/)() | 共有参照カウンタをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../string/) [ToString](./tostring/)() const | C# の [Object.ToString()](./tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | C# の typeof([System.Object](./)) 構文を実装します。 |
| void [Unlock](./unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../lockcontext/) センティリオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](./weakrefadded/)() | 弱参照カウンタをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](./weakrefremoved/)() | 弱参照カウンタをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](./~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 型定義

| 型エイリアス | 説明 |
| --- | --- |
| [ptr](./ptr/) | スマートポインタ型のエイリアスです。 |

## 備考

C# の [System.Object](./) クラスで利用可能なメソッドに加えて、翻訳コード環境固有の概念のサポートも可能にします。これには、スマートポインタクラス ([System::SmartPtr](../smartptr/), [System::WeakPtr](../weakptr/), [System::DynamicWeakPtr](../dynamicweakptr/)) が使用する参照カウントや、メモリ管理、デバッグなどに関連するその他のサービスが含まれます。

各 [Object](./) には 2 つの参照カウンタがあります：共有参照カウンタと弱参照カウンタです。弱参照カウンタは常に [Object](./) 自体ではなく、分離されたデータ構造に格納され、弱ポインタが参照オブジェクトより長く存続できるようにします。スマート参照カウンタは ENABLE_EXTERNAL_REFCOUNT マクロの状態に応じて、オブジェクト自身または同じ分離構造に格納されます。既定ではデバッグビルドで有効、リリースビルドで無効です。スマートポインタカウンタがオブジェクト自身に格納される場合、弱ポインタが存在する場合にのみ分離データ構造が作成されます。そうでない場合はオブジェクトと共に作成されます。

すべてのスマートポインタはこの 2 つの参照カウンタを使用し、同一かつ唯一の所有権グループに貢献します。

[Object](./) サブクラスがスタック上に作成された場合、そのインスタンスへのスマートポインタは作成できません。そうしないとスタック削除の問題が発生します。

この型はスタック上の値型として、または [System::MakeObject()](../makeobject/) 関数を使用してヒープに割り当てることができます。オブジェクトが割り当てられたら、これら 2 つの使用ケースを混在させてはいけません：スタック割り当てオブジェクトへの [SmartPtr](../smartptr/) ポインタを保持することは厳格に禁止されています。

## 参照

* Namespace [System](../)
* Library [Aspose.Slides](../../)