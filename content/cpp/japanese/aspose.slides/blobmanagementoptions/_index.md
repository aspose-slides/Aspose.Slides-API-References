---
title: BlobManagementOptions
second_title: Aspose.Slides for C++ API リファレンス
description: BLOB の取り扱いルールやその他の BLOB 設定を管理するために使用できるオプションを表します。
type: docs
weight: 196
url: /ja/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions クラス

BLOB の取り扱いルールやその他の BLOB 設定を管理するために使用できるオプションを表します。

```cpp
class BlobManagementOptions : public Aspose::Slides::IBlobManagementOptions
```

## メソッド

| メソッド | 説明 |
| --- | --- |
|  [BlobManagementOptions](./blobmanagementoptions/)() | 新しいデフォルトの blob management options を作成します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくありませんが、C#-style の浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくありませんが、C#-style の浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部目的のみです。 |
| **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() override | このプロパティは、BLOB を扱う際に一時ファイルを作成できるかどうかを定義します。一時ファイルの作成はメモリ消費を大幅に削減しますが、ファイル作成の権限が必要です。 |
| **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() override | すべての BLOB がメモリ上で占有できる最大合計サイズ（バイト単位）を定義します。デフォルトではすべての BLOB がメモリにロードされ、上限に達した時点で一時ファイル等の代替手段が使用されます。メモリに BLOB を保持するとパフォーマンスは最大化されますが、メモリ使用量が増加する可能性があります。このプロパティを使用して環境や要件に合わせた動作を調整してください。 |
| [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() override | このプロパティは、[Presentation](../presentation/) クラスのインスタンスがインスタンス期間中にソース（ファイルまたはストリーム）の所有者になれるかどうかを定義します。所有者である場合、ソースはロックされます。これにより BLOB のメモリ消費とパフォーマンスが向上しますが、[Presentation](../presentation/) のインスタンス期間中はソース（ストリームまたはファイル）を変更できなくなります。 |
| [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() override | 一時ファイルが作成されるルートパスです。[System](../../system/) 暫定ディレクトリがデフォルトで使用されます。ホスティングプロセスはそこにファイルとフォルダーを作成する権限を持つ必要があります。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロック機構を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローンを可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 文字列と nullptr の場合の [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 文字列の場合の [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 共有参照カウントを指定された値だけ減少させます。 |
| void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) override | このプロパティは、BLOB を扱う際に一時ファイルを作成できるかどうかを定義します。一時ファイルの作成はメモリ消費を大幅に削減しますが、ファイル作成の権限が必要です。 |
| void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) override | すべての BLOB がメモリ上で占有できる最大合計サイズ（バイト単位）を定義します。デフォルトではすべての BLOB がメモリにロードされ、上限に達した時点で一時ファイル等の代替手段が使用されます。メモリに BLOB を保持するとパフォーマンスは最大化されますが、メモリ使用量が増加する可能性があります。このプロパティを使用して環境や要件に合わせた動作を調整してください。 |
| void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) override | このプロパティは、[Presentation](../presentation/) クラスのインスタンスがインスタンス期間中にソース（ファイルまたはストリーム）の所有者になれるかどうかを定義します。所有者である場合、ソースはロックされます。これにより BLOB のメモリ消費とパフォーマンスが向上しますが、[Presentation](../presentation/) のインスタンス期間中はソース（ストリームまたはファイル）を変更できなくなります。 |
| void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) override | 一時ファイルが作成されるルートパスです。[System](../../system/) 暫定ディレクトリがデフォルトで使用されます。ホスティングプロセスはそこにファイルとフォルダーを作成する権限を持つ必要があります。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を共有ポインターではなく弱参照ポインターに設定します。コンテナ内のポインターを弱参照モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウントの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインターまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインターまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のアンロック機構を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインターまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインターまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IBlobManagementOptions](../iblobmanagementoptions/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)