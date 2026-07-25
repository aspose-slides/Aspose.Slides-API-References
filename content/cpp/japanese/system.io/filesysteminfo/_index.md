---
title: FileSystemInfo
second_title: Aspose.Slides for C++ APIリファレンス
description: "FileInfo と DirectoryInfo の基底クラスです。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てる必要があります。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうするとランタイムエラーやアサーション障害が発生します。このクラスは必ず System::SmartPtr ポインタでラップし、そのポインタを関数への引数として渡してください。"
type: docs
weight: 300
url: /ja/system.io/filesysteminfo/
---
## FileSystemInfo クラス


[FileInfo](../fileinfo/) と [DirectoryInfo](../directoryinfo/) の基底クラスです。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうするとランタイムエラーやアサーション障害が発生します。このクラスは必ず [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。

```cpp
class FileSystemInfo : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual void [Delete](./delete/)() | 現在のオブジェクトが表すエンティティを削除します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用です。 |
| virtual void [Finalize](./finalize/)() | 何もしません。 |
| [FileAttributes](../fileattributes/) [get_Attributes](./get_attributes/)() | 現在のオブジェクトが表すエンティティの属性を返します。 |
| [DateTime](../../system/datetime/) [get_CreationTime](./get_creationtime/)() | 現在のオブジェクトが表すエンティティの作成時刻をローカル時間で返します。 |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](./get_creationtimeutc/)() | 現在のオブジェクトが表すエンティティの作成時刻を UTC 時間で返します。 |
| virtual **bool** [get_Exists](./get_exists/)() | 現在のオブジェクトが表すパスで参照されるエンティティが存在するかどうかを判断します。 |
| [String](../../system/string/) [get_Extension](./get_extension/)() | 現在のオブジェクトが表すファイルの拡張子を返します。 |
| virtual [String](../../system/string/) [get_FullName](./get_fullname/)() | 現在のオブジェクトが表すエンティティの完全な名前（パスを含む）を返します。 |
| [DateTime](../../system/datetime/) [get_LastAccessTime](./get_lastaccesstime/)() | 現在のオブジェクトが表すエンティティの最終アクセス時刻をローカル時間で返します。 |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](./get_lastaccesstimeutc/)() | 現在のオブジェクトが表すエンティティの最終アクセス時刻を UTC 時間で返します。 |
| [DateTime](../../system/datetime/) [get_LastWriteTime](./get_lastwritetime/)() | 現在のオブジェクトが表すエンティティの最終書き込み時刻をローカル時間で返します。 |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](./get_lastwritetimeutc/)() | 現在のオブジェクトが表すエンティティの最終書き込み時刻を UTC 時間で返します。 |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | 現在のオブジェクトが表すエンティティの名前を返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造体を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかをチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントによるロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| void [Refresh](./refresh/)() | 現在のオブジェクトの状態をリフレッシュします。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウンターを減少させます。 |
| void [set_Attributes](./set_attributes/)([FileAttributes](../fileattributes/)) | 現在のオブジェクトが表すエンティティに指定された属性を設定します。 |
| void [set_CreationTime](./set_creationtime/)([DateTime](../../system/datetime/)) | 現在のオブジェクトが表すエンティティの作成時刻をローカル時間として設定します。 |
| void [set_CreationTimeUtc](./set_creationtimeutc/)([DateTime](../../system/datetime/)) | 現在のオブジェクトが表すエンティティの作成時刻を UTC 時間として設定します。 |
| void [set_LastAccessTime](./set_lastaccesstime/)([DateTime](../../system/datetime/)) | 現在のオブジェクトが表すエンティティの最終アクセス時刻をローカル時間として設定します。 |
| void [set_LastAccessTimeUtc](./set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | 現在のオブジェクトが表すエンティティの最終アクセス時刻を UTC 時間として設定します。 |
| void [set_LastWriteTime](./set_lastwritetime/)([DateTime](../../system/datetime/)) | 現在のオブジェクトが表すエンティティの最終書き込み時刻をローカル時間として設定します。 |
| void [set_LastWriteTimeUtc](./set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | 現在のオブジェクトが表すエンティティの最終書き込み時刻を UTC 時間として設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンターの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() ステートメントのアンロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [Object](../../system/object/)
* 名前空間 [System::IO](../)
* ライブラリ [Aspose.Slides](../../)