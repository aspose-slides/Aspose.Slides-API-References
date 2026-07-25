---
title: FileInfo
second_title: Aspose.Slides for C++ API リファレンス
description: "このクラスはファイルへのパスおよびそのパスが指すファイルを表し、操作用のメソッドを提供します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上でインスタンスを作成したり operator new を使用したりしないでください。これらは実行時エラーやアサーション違反の原因となります。このクラスは常に System::SmartPtr ポインタでラップし、そのポインタを関数への引数として渡すようにしてください。"
type: docs
weight: 274
url: /ja/system.io/fileinfo/
---
## FileInfo クラス


Represents a path to a file and a file referred to by this path and provides methods for manipulating it. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class FileInfo : public System::IO::FileSystemInfo
```

## メソッド

| Method | Description |
| --- | --- |
| [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)() | 現在のオブジェクトで表されるファイルを開き、UTF-8 エンコーディングでテキストを書き込みます。'Append' モードで、共有は行いません。 |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&) | 現在のオブジェクトで表されるファイルを指定された場所にコピーします。宛先ファイルが既に存在する場合、コピーは失敗します。 |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&, **bool**) | 現在のオブジェクトで表されるファイルを指定された場所にコピーします。パラメータは、既存の宛先ファイルを上書きするかどうかを指定します。 |
| [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)() | 現在のオブジェクトで表されるパスが示す場所にファイルを作成し、トランケートモードで共有なしで読み書き用に開きます。 |
| [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)() | 現在のオブジェクトで表されるパスが示す場所にファイルを作成し、UTF-8 エンコーディングでテキストを書き込むために共有なしで開きます。 |
| void [Decrypt](./decrypt/)() | 実装されていません。 |
| void [Delete](./delete/)() override | 現在のオブジェクトで表されるファイルを削除します。 |
| void [Encrypt](./encrypt/)() | 実装されていません。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# の [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
|  [FileInfo](./fileinfo/)(const [String](../../system/string/)\&) | [FileInfo](./) クラスの新しいインスタンスを構築し、指定されたファイルを表します。 |
| virtual void [Finalize](../filesysteminfo/finalize/)() | 何もしません。 |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | 現在のオブジェクトで表されるエンティティの属性を返します。 |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | 現在のオブジェクトで表されるエンティティの作成時刻をローカル時間で返します。 |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | 現在のオブジェクトで表されるエンティティの作成時刻を UTC 時間で返します。 |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Directory](./get_directory/)() | 現在のオブジェクトで表されるファイルが所在するディレクトリを表す [DirectoryInfo](../directoryinfo/) オブジェクトを返します。 |
| [String](../../system/string/) [get_DirectoryName](./get_directoryname/)() | 現在のオブジェクトで表されるファイルが所在するディレクトリのフルパス名を返します。 |
| **bool** [get_Exists](./get_exists/)() override | ファイルが存在するかどうかを示す値を返します。 |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | 現在のオブジェクトで表されるファイルの拡張子を返します。 |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | 現在のオブジェクトで表されるエンティティのフルパス名（パスを含む）を返します。 |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | ReadOnly 属性が設定されているかどうかを示す値を返します。 |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | 現在のオブジェクトで表されるエンティティの最終アクセス時刻をローカル時間で返します。 |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | 現在のオブジェクトで表されるエンティティの最終アクセス時刻を UTC 時間で返します。 |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | 現在のオブジェクトで表されるエンティティの最終書き込み時刻をローカル時間で返します。 |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | 現在のオブジェクトで表されるエンティティの最終書き込み時刻を UTC 時間で返します。 |
| **int64_t** [get_Length](./get_length/)() | ファイルのサイズをバイト単位で返します。 |
| [String](../../system/string/) [get_Name](./get_name/)() override | ファイル名を返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロック機構を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | 現在のオブジェクトで表されるファイルを指定された場所へ移動します。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成し、すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/)) | 指定されたモードで、共有なしで現在のオブジェクトで表されるファイルを読み書き用に開きます。 |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/)) | 指定されたモードとアクセス種別で、共有なしで現在のオブジェクトで表されるファイルを開きます。 |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | 指定されたモード、アクセス種別、共有オプションで、現在のオブジェクトで表されるファイルを開きます。 |
| [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)() | 現在のオブジェクトで表されるファイルを読み取り専用で開き、'Open' モードで読み取りの共有アクセスを行います。 |
| [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)() | 現在のオブジェクトで表されるパスが示す場所にある既存のファイルを UTF-8 エンコーディングでテキスト読み取り用に、共有なしで開きます。 |
| [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)() | 現在のオブジェクトで表されるファイルを書き込み専用で開き、'OpenOrCreate' モードで共有なしで開きます。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| void [Refresh](../filesysteminfo/refresh/)() | 現在のオブジェクトの状態をリフレッシュします。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 指定された宛先ファイルの内容を現在の [FileInfo](./) オブジェクトで表されるファイルで置き換え、置き換えられたファイルのバックアップを作成します。 |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | 指定された宛先ファイルの内容を現在の [FileInfo](./) オブジェクトで表されるファイルで置き換え、置き換えられたファイルのバックアップを作成します。 |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | 現在のオブジェクトで表されるエンティティに指定された属性を設定します。 |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | 現在のオブジェクトで表されるエンティティの作成時刻をローカル時間で設定します。 |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | 現在のオブジェクトで表されるエンティティの作成時刻を UTC 時間で設定します。 |
| void [set_IsReadOnly](./set_isreadonly/)(**bool**) | ファイルの ReadOnly 属性を設定または解除します。 |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | 現在のオブジェクトで表されるエンティティの最終アクセス時刻をローカル時間で設定します。 |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | 現在のオブジェクトで表されるエンティティの最終アクセス時刻を UTC 時間で設定します。 |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | 現在のオブジェクトで表されるエンティティの最終書き込み時刻をローカル時間で設定します。 |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | 現在のオブジェクトで表されるエンティティの最終書き込み時刻を UTC 時間で設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を強参照ではなく弱参照ポインタに設定します。コンテナ内のポインタを弱モードに切り替えることが可能です。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | 現在のオブジェクトで表されるパスを返します。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄し、すべての内部データ構造を解放します。 |
## 参照

* クラス [FileSystemInfo](../filesysteminfo/)
* 名前空間 [System::IO](../)
* ライブラリ [Aspose.Slides](../../)