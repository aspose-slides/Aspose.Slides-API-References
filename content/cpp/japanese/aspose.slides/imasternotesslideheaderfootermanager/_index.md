---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides for C++ API リファレンス
description: マスターノートスライドのフッター、日付時刻、ページ番号プレースホルダーおよびすべての子プレースホルダーの動作を保持するマネージャーを表します。子プレースホルダーは、依存するノートスライドに含まれるプレースホルダーを意味します。依存するノートスライドはマスターノートスライドを使用し、依存しています。
type: docs
weight: 2900
url: /ja/aspose.slides/imasternotesslideheaderfootermanager/
---
## IMasterNotesSlideHeaderFooterManager クラス

Master notes スライドのフッター、日付時刻、ページ番号プレースホルダーおよびすべての子プレースホルダーの動作を保持するマネージャーを表します。子プレースホルダーは、依存するノートスライドに含まれるプレースホルダーを意味します。依存するノートスライドは master notes スライドを使用し、依存しています。

```cpp
class IMasterNotesSlideHeaderFooterManager : public virtual Aspose::Slides::IBaseHandoutNotesSlideHeaderFooterManag
```

## メソッド

| Method | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN が等しいとみなされます。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN が等しいとみなされます。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual **bool** [get_IsDateTimeVisible](../ibaseslideheaderfootermanager/get_isdatetimevisible/)() | 日付時刻プレースホルダーが存在することを示す値を取得します。Read**bool**。 |
| virtual **bool** [get_IsFooterVisible](../ibaseslideheaderfootermanager/get_isfootervisible/)() | フッタープレースホルダーが存在することを示す値を取得します。Read **bool**。 |
| virtual **bool** [get_IsHeaderVisible](../ibasehandoutnotesslideheaderfootermanag/get_isheadervisible/)() | ヘッダープレースホルダーが存在することを示す値を取得します。Read **bool**。 |
| virtual **bool** [get_IsSlideNumberVisible](../ibaseslideheaderfootermanager/get_isslidenumbervisible/)() | ページ番号プレースホルダーが存在することを示す値を取得します。Read**bool**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) | マスターノートスライドの日時プレースホルダーとすべての子日時プレースホルダーにテキストを設定します。子プレースホルダーは、依存するノートスライドに含まれるプレースホルダーを意味します。依存するノートスライドはマスターノートスライドを使用し、依存しています。 |
| virtual void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) | マスターノートスライドの日時プレースホルダーとすべての子日時プレースホルダーの表示状態を変更します。子プレースホルダーは、依存するノートスライドに含まれるプレースホルダーを意味します。依存するノートスライドはマスターノートスライドを使用し、依存しています。 |
| virtual void [SetDateTimeText](../ibaseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) | スライドの日時プレースホルダーにテキストを設定します。 |
| virtual void [SetDateTimeVisibility](../ibaseslideheaderfootermanager/setdatetimevisibility/)(**bool**) | スライドの日時プレースホルダーの表示状態を変更します。 |
| virtual void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) | マスターノートスライドのフッタープレースホルダーとすべての子フッタープレースホルダーにテキストを設定します。子プレースホルダーは、依存するノートスライドに含まれるプレースホルダーを意味します。依存するノートスライドはマスターノートスライドを使用し、依存しています。 |
| virtual void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) | マスターノートスライドのフッタープレースホルダーとすべての子フッタープレースホルダーの表示状態を変更します。子プレースホルダーは、依存するノートスライドに含まれるプレースホルダーを意味します。依存するノートスライドはマスターノートスライドを使用し、依存しています。 |
| virtual void [SetFooterText](../ibaseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) | スライドのフッタープレースホルダーにテキストを設定します。 |
| virtual void [SetFooterVisibility](../ibaseslideheaderfootermanager/setfootervisibility/)(**bool**) | スライドのフッタープレースホルダーの表示状態を変更します。 |
| virtual void [SetHeaderAndChildHeadersText](./setheaderandchildheaderstext/)([System::String](../../system/string/)) | マスターノートスライドのヘッダープレースホルダーとすべての子ヘッダープレースホルダーにテキストを設定します。子プレースホルダーは、依存するノートスライドに含まれるプレースホルダーを意味します。依存するノートスライドはマスターノートスライドを使用し、依存しています。 |
| virtual void [SetHeaderAndChildHeadersVisibility](./setheaderandchildheadersvisibility/)(**bool**) | マスターノートスライドのヘッダープレースホルダーとすべての子ヘッダープレースホルダーの表示状態を変更します。子プレースホルダーは、依存するノートスライドに含まれるプレースホルダーを意味します。依存するノートスライドはマスターノートスライドを使用し、依存しています。 |
| virtual void [SetHeaderText](../ibasehandoutnotesslideheaderfootermanag/setheadertext/)([System::String](../../system/string/)) | スライドのヘッダープレースホルダーにテキストを設定します。 |
| virtual void [SetHeaderVisibility](../ibasehandoutnotesslideheaderfootermanag/setheadervisibility/)(**bool**) | スライドのヘッダープレースホルダーの表示状態を変更します。 |
| virtual void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) | マスターノートスライドのページ番号プレースホルダーとすべての子ページ番号プレースホルダーの表示状態を変更します。子プレースホルダーは、依存するノートスライドに含まれるプレースホルダーを意味します。依存するノートスライドはマスターノートスライドを使用し、依存しています。 |
| virtual void [SetSlideNumberVisibility](../ibaseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) | スライドのページ番号プレースホルダーの表示状態を変更します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱いポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱いモードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IBaseHandoutNotesSlideHeaderFooterManag](../ibasehandoutnotesslideheaderfootermanag/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)