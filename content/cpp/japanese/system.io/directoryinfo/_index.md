---
title: DirectoryInfo
second_title: Aspose.Slides for C++ APIリファレンス
description: "ファイルシステムのパスと、そのパスが指すディレクトリを表し、ディレクトリを操作するためのインスタンスメソッドを提供します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new でこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーション障害が発生します。常にこのクラスを System::SmartPtr ポインタでラップし、そのポインタを関数への引数として渡してください。"
type: docs
weight: 248
url: /ja/system.io/directoryinfo/
---
## DirectoryInfo クラス

ファイルシステムのパスと、そのパスが指すディレクトリを表し、ディレクトリを操作するためのインスタンスメソッドを提供します。  
このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。  
スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうすると実行時エラーやアサーションの失敗が発生します。  
常にこのクラスを [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。

```cpp
class DirectoryInfo : public System::IO::FileSystemInfo
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| void [Create](./create/)() | 現在のオブジェクトが表すパスにディレクトリを作成します。 |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [CreateSubdirectory](./createsubdirectory/)(const [String](../../system/string/)\&) | 指定されたパスにサブディレクトリを作成します。 |
| void [Delete](./delete/)() override | 現在のオブジェクトが表すパスが指すディレクトリが空の場合、そのディレクトリを削除します。 |
| void [Delete](./delete/)(**bool**) | 現在のオブジェクトが表すパスが指すディレクトリを削除します。ディレクトリが空でない場合に、その内容を再帰的に削除するかどうかをパラメータで指定します。 |
|  [DirectoryInfo](./directoryinfo/)(const [String](../../system/string/)\&) | 指定されたパスで [DirectoryInfo](./) クラスのインスタンスを構築します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)() | 現在のオブジェクトが表すディレクトリ内にあるすべてのディレクトリを含む列挙可能なコレクションを返します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&) | 現在のオブジェクトが表すディレクトリ内で、指定された検索条件を満たすディレクトリを検索します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 現在のオブジェクトが表すディレクトリ、またはそのディレクトリをルートとする全ディレクトリツリー内で、指定された検索条件を満たすディレクトリを検索します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)() | 現在のオブジェクトが表すディレクトリ内にあるすべてのファイルを含む列挙可能なコレクションを返します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&) | 現在のオブジェクトが表すディレクトリ内で、指定された検索条件を満たすファイルを検索します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 現在のオブジェクトが表すディレクトリ、またはそのディレクトリをルートとする全ディレクトリツリー内で、指定された検索条件を満たすファイルを検索します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)() | 現在のオブジェクトが表すディレクトリ内にあるすべてのファイルとディレクトリを含む列挙可能なコレクションを返します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&) | 現在のオブジェクトが表すディレクトリ内で、指定された検索条件を満たすファイルとディレクトリを検索します。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 現在のオブジェクトが表すディレクトリ、またはそのディレクトリをルートとする全ディレクトリツリー内で、指定された検索条件を満たすファイルとディレクトリを検索します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# の [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、二つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN はどの値とも等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、二つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual void [Finalize](../filesysteminfo/finalize/)() | 何もしません。 |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | 現在のオブジェクトが表すエンティティの属性を返します。 |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | 現在のオブジェクトが表すエンティティの作成時刻（ローカル時間）を返します。 |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | 現在のオブジェクトが表すエンティティの作成時刻（UTC 時間）を返します。 |
| **bool** [get_Exists](./get_exists/)() override | 現在のオブジェクトが表すパスが既存のディレクトリを指すかどうかを判定します。 |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | 現在のオブジェクトが表すファイルの拡張子を返します。 |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | 現在のオブジェクトが表すエンティティの完全な名前（パスを含む）を返します。 |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | 現在のオブジェクトが表すエンティティの最終アクセス時刻（ローカル時間）を返します。 |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | 現在のオブジェクトが表すエンティティの最終アクセス時刻（UTC 時間）を返します。 |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | 現在のオブジェクトが表すエンティティの最終書き込み時刻（ローカル時間）を返します。 |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | 現在のオブジェクトが表すエンティティの最終書き込み時刻（UTC 時間）を返します。 |
| [String](../../system/string/) [get_Name](./get_name/)() override | 現在のオブジェクトが表すパスが指すエンティティの名前を返します。 |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Parent](./get_parent/)() | 現在のオブジェクトが表すディレクトリの親ディレクトリを指すパスを表す [DirectoryInfo](./) オブジェクトへの共有ポインタを返します。 |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Root](./get_root/)() | 現在のオブジェクトが表すディレクトリのルートディレクトリを指すパスを表す [DirectoryInfo](./) オブジェクトへの共有ポインタを返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)() | 現在のオブジェクトが表すディレクトリ内にあるすべてのディレクトリを表す [DirectoryInfo](./) オブジェクトへの共有ポインタを含む配列を返します。 |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&) | 現在のオブジェクトが表すディレクトリ内で、指定された検索条件を満たすディレクトリを検索します。 |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 現在のオブジェクトが表すディレクトリ、またはそのディレクトリをルートとする全ディレクトリツリー内で、指定された検索条件を満たすディレクトリを検索します。 |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)() | 現在のオブジェクトが表すディレクトリ内にあるすべてのディレクトリを表す [FileInfo](../fileinfo/) オブジェクトへの共有ポインタを含む配列を返します。 |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&) | 現在のオブジェクトが表すディレクトリ内で、指定された検索条件を満たすファイルを検索します。 |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 現在のオブジェクトが表すディレクトリ、またはそのディレクトリをルートとする全ディレクトリツリー内で、指定された検索条件を満たすファイルを検索します。 |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)() | 現在のオブジェクトが表すディレクトリ内にあるすべてのファイルとディレクトリを表す [FileSystemInfo](../filesysteminfo/) オブジェクトへの共有ポインタを含む配列を返します。 |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&) | 現在のオブジェクトが表すディレクトリ内で、指定された検索条件を満たすファイルとディレクトリを検索します。 |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | 現在のオブジェクトが表すディレクトリ、またはそのディレクトリをルートとする全ディレクトリツリー内で、指定された検索条件を満たすファイルとディレクトリを検索します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似で、カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかをチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センリオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似で、カスタム型のクローン作成を可能にします。 |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | 現在のオブジェクトが表すディレクトリとそのすべての内容を指定された場所へ移動します。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成し、すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| void [Refresh](../filesysteminfo/refresh/)() | 現在のオブジェクトの状態をリフレッシュします。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | 現在のオブジェクトが表すエンティティに指定された属性を設定します。 |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | 現在のオブジェクトが表すエンティティの作成時刻をローカル時間として設定します。 |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | 現在のオブジェクトが表すエンティティの作成時刻を UTC 時間として設定します。 |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | 現在のオブジェクトが表すエンティティの最終アクセス時刻をローカル時間として設定します。 |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | 現在のオブジェクトが表すエンティティの最終アクセス時刻を UTC 時間として設定します。 |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | 現在のオブジェクトが表すエンティティの最終書き込み時刻をローカル時間として設定します。 |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | 現在のオブジェクトが表すエンティティの最終書き込み時刻を UTC 時間として設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を共有ポインタではなく弱ポインタに設定します。コンテナ内のポインタを弱参照モードに切り替えることが可能です。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | 現在のオブジェクトが表すパスを含む文字列を返します。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センリオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄し、すべての内部データ構造を解放します。 |

## 参照

* クラス [FileSystemInfo](../filesysteminfo/)
* 名前空間 [System::IO](../)
* ライブラリ [Aspose.Slides](../../)