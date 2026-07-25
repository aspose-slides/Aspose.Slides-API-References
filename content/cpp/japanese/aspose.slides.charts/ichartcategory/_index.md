---
title: IChartCategory
second_title: Aspose.Slides for C++ API リファレンス
description: チャートカテゴリを表します。
type: docs
weight: 586
url: /ja/aspose.slides.charts/ichartcategory/
---
## IChartCategory クラス

チャートカテゴリを表します。

```cpp
class IChartCategory : public virtual System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部使用専用です。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_AsCell](./get_ascell/)() | [IChartDataCell](../ichartdatacell/) オブジェクトを返します。カテゴリがマルチレベルの場合、レベル "0" に [IChartDataCell](../ichartdatacell/) オブジェクトが使用されます。[IChartDataCell](../ichartdatacell/) を参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_AsLiteral](./get_asliteral/)() | UseCell が false の場合は AsLiteral を返します。[System::Object](../../system/object/) を参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_GroupingLevel](./get_groupinglevel/)(**int32_t**) | 指定されたインデックスのチャートカテゴリのグループ化レベルを返します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryLevelsManager](../ichartcategorylevelsmanager/)\> [get_GroupingLevels](./get_groupinglevels/)() | チャートカテゴリのグループ化レベルの値を管理するコンテナです。マルチレベルカテゴリは複数のグループ化レベルを含みます。グループ化レベルのインデックスは 0 から始まります。読み取り専用 [IChartCategoryLevelsManager](../ichartcategorylevelsmanager/)。 |
| virtual **bool** [get_UseCell](./get_usecell/)() | true の場合、AsCell プロパティが有効です。つまり、ワークシートがカテゴリの保存に使用されます（このケースはマルチレベルカテゴリをサポートします）。false の場合、AsLiteral プロパティが有効です。つまり、ワークシートはカテゴリの保存に使用されず（このケースはマルチレベルカテゴリをサポートしません）。読み取り専用 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Value](./get_value/)() | UseCell が true の場合、このプロパティは [get_AsCell()](./get_ascell/)->get(set)_Value() プロパティを表します。UseCell が false の場合、このプロパティは AsLiteral プロパティを表します。[System::Object](../../system/object/) を参照してください。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの C# アナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。[System.Object.GetType()](../../system/object/gettype/) 呼び出しの C# アナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文によるロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの C# アナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| virtual void [Remove](./remove/)() | チャートからカテゴリを削除します。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_AsCell](./set_ascell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) | [IChartDataCell](../ichartdatacell/) オブジェクトを設定します。カテゴリがマルチレベルの場合、レベル "0" に [IChartDataCell](../ichartdatacell/) オブジェクトが使用されます。[IChartDataCell](../ichartdatacell/) に書き込みます。 |
| virtual void [set_AsLiteral](./set_asliteral/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | UseCell が false の場合、AsLiteral を設定します。[System::Object](../../system/object/) に書き込みます。 |
| virtual void [set_Value](./set_value/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | UseCell が true の場合、このプロパティは [get_AsCell()](./get_ascell/)->get(set)_Value() プロパティを表します。UseCell が false の場合、このプロパティは AsLiteral プロパティを表します。[System::Object](../../system/object/) に書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | [Object.ToString()](../../system/object/tostring/) メソッドの C# アナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [Object](../../system/object/)
* 名前空間 [Aspose::Slides::Charts](../)
* ライブラリ [Aspose.Slides](../../)