---
title: "System::IO"
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 573
url: /ja/system.io/
---
## クラス

| クラス | 説明 |
| --- | --- |
| [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) | [System.IO.Stream](./stream/) のようなラッパーを表します。std::basic_iostream およびその派生オブジェクト用です。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でこの型のインスタンスを作成しないでください。実行時エラーやアサーション失敗の原因になります。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) | [System.IO.Stream](./stream/) のようなラッパーを表します。std::basic_istream およびその派生オブジェクト用です。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でこの型のインスタンスを作成しないでください。実行時エラーやアサーション失敗の原因になります。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) | [System.IO.Stream](./stream/) のようなラッパーを表します。std::basic_ostream およびその派生オブジェクト用です。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でこの型のインスタンスを作成しないでください。実行時エラーやアサーション失敗の原因になります。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) | [System::IO::Stream](./stream/) のようなストリームをラップするバッファを表し、std::iostream のようなストリームの内部バッファとして使用できるようにします。 |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) | [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) を内部バッファとして使用する std::iostream のようなラッパーを表します。 |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) | [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) を内部バッファとして使用する std::istream のようなラッパーを表します。 |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) | [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) を内部バッファとして使用する std::ostream のようなラッパーを表します。 |
| [BinaryReader](./binaryreader/) | 原始データ型を特定のエンコーディングでバイナリデータとして読み取るリーダーを表します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でこの型のインスタンスを作成しないでください。実行時エラーやアサーション失敗の原因になります。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [BinaryWriter](./binarywriter/) | 原始型の値をバイトストリームに書き込むライターを表します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でこの型のインスタンスを作成しないでください。実行時エラーやアサーション失敗の原因になります。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [BufferedStream](./bufferedstream/) | 別のストリームの上にバッファリング層を追加します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でこの型のインスタンスを作成しないでください。実行時エラーやアサーション失敗の原因になります。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [Details_DirectoryNotFoundException](./details_directorynotfoundexception/) |  |
| [Details_DriveNotFoundException](./details_drivenotfoundexception/) |  |
| [Details_EndOfStreamException](./details_endofstreamexception/) |  |
| [Details_FileLoadException](./details_fileloadexception/) |  |
| [Details_FileNotFoundException](./details_filenotfoundexception/) | ディスク上に存在しないファイルにアクセスしようとしたときにスローされる例外です。インスタンスを手動で作成しないでください。代わりに FileNotFoundException クラスを使用してください。FileNotFoundException クラスのインスタンスを [System::SmartPtr](../system/smartptr/) でラップしないでください。 |
| [Details_InvalidDataException](./details_invaliddataexception/) |  |
| [Details_IOException](./details_ioexception/) |  |
| [Details_PathTooLongException](./details_pathtoolongexception/) |  |
| [Directory](./directory/) | ディレクトリを操作するメソッドを含みます。インスタンスサービスを持たない静的型です。いかなる方法でもインスタンスを作成しないでください。 |
| [DirectoryInfo](./directoryinfo/) | ファイルシステムパスと、そのパスが参照するディレクトリを表し、ディレクトリを操作するインスタンスメソッドを提供します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でこの型のインスタンスを作成しないでください。実行時エラーやアサーション失敗の原因になります。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [File](./file/) | ファイルを操作するメソッドを提供します。インスタンスサービスを持たない静的型です。いかなる方法でもインスタンスを作成しないでください。 |
| [FileInfo](./fileinfo/) | ファイルへのパスとそのパスが参照するファイルを表し、ファイルを操作するメソッドを提供します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でこの型のインスタンスを作成しないでください。実行時エラーやアサーション失敗の原因になります。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [FileStream](./filestream/) | 同期および非同期の読み書き操作をサポートするファイルストリームを表します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でこの型のインスタンスを作成しないでください。実行時エラーやアサーション失敗の原因になります。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [FileSystemInfo](./filesysteminfo/) | [FileInfo](./fileinfo/) と [DirectoryInfo](./directoryinfo/) の基底クラスです。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でこの型のインスタンスを作成しないでください。実行時エラーやアサーション失敗の原因になります。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [FileSystemInfoStat](./filesysteminfostat/) | ファイルまたはディレクトリに関する情報を表します。 |
| [MemoryStream](./memorystream/) | メモリから読み書きするストリームを表します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でこの型のインスタンスを作成しないでください。実行時エラーやアサーション失敗の原因になります。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [Path](./path/) | パスを操作するメソッドを提供します。インスタンスサービスを持たない静的型です。いかなる方法でもインスタンスを作成しないでください。 |
| [STDIOStreamWrapperBase](./stdiostreamwrapperbase/) | [System.IO.Stream](./stream/) のようなラッパーの基底クラスを表します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でこの型のインスタンスを作成しないでください。実行時エラーやアサーション失敗の原因になります。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [Stream](./stream/) | 各種ストリーム実装の基底クラスです。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でこの型のインスタンスを作成しないでください。実行時エラーやアサーション失敗の原因になります。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [StreamReader](./streamreader/) | バイトストリームから文字を読み取るリーダーを表します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でこの型のインスタンスを作成しないでください。実行時エラーやアサーション失敗の原因になります。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [StreamWriter](./streamwriter/) | バイトストリームへ文字を書き込むライターを表します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でこの型のインスタンスを作成しないでください。実行時エラーやアサーション失敗の原因になります。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [StringReader](./stringreader/) | 文字列から文字を読み取るリーダーを表します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でこの型のインスタンスを作成しないでください。実行時エラーやアサーション失敗の原因になります。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [StringWriter](./stringwriter/) | 情報を書き込む [TextWriter](./textwriter/) を実装します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でこの型のインスタンスを作成しないでください。実行時エラーやアサーション失敗の原因になります。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [TextReader](./textreader/) | 異なるソースから文字列シーケンスを読み取るリーダーを表すクラスの基底クラスです。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でこの型のインスタンスを作成しないでください。実行時エラーやアサーション失敗の原因になります。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [TextWriter](./textwriter/) | 異なる宛先へ文字列シーケンスを書き込むライターを表すクラスの基底クラスです。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でこの型のインスタンスを作成しないでください。実行時エラーやアサーション失敗の原因になります。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
| [UnmanagedMemoryStream](./unmanagedmemorystream/) | 管理対象外メモリへのアクセスを提供します。このクラスのオブジェクトは [System::MakeObject()](../system/makeobject/) 関数を使用してのみ割り当てるべきです。スタック上や operator new でこの型のインスタンスを作成しないでください。実行時エラーやアサーション失敗の原因になります。常にこのクラスを [System::SmartPtr](../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡してください。 |
## 関数

| 関数 | 説明 |
| --- | --- |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_istream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/)) | std::basic_istream のようなストリーム用ラッパー関数です。 |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_ostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/)) | std::basic_ostream のようなストリーム用ラッパー関数です。 |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_iostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/), [STDIOStreamPositionPreference](./stdiostreampositionpreference/)) | std::basic_iostream のようなストリーム用ラッパー関数です。 |
## 列挙型

| 列挙型 | 説明 |
| --- | --- |
| [FileAccess](./fileaccess/) | ファイルを開く際のアクセス種別を指定します。 |
| [FileAttributes](./fileattributes/) | ディレクトリまたはファイルの属性を表します。 |
| [FileMode](./filemode/) | ファイルの開き方を指定します。 |
| [FileOptions](./fileoptions/) | [FileStream](./filestream/) オブジェクト作成時の高度なオプションを表します。 |
| [FileShare](./fileshare/) | 開かれるファイルに対して他の [FileStream](./filestream/) オブジェクトが持つことのできるアクセス種別を指定します。 |
| [SearchOption](./searchoption/) | 検索をカレントディレクトリのみで実行するか、カレントディレクトリとすべてのサブディレクトリで実行するかを指定します。 |
| [SeekOrigin](./seekorigin/) | シーク位置を指定する基準となるストリーム内の参照位置を指定します。 |
| [STDIOStreamWrappingMode](./stdiostreamwrappingmode/) | ラッパーが std::iostream のようなストリームで実行する I/O 操作モードを指定します。 |
| [STDIOStreamPositionPreference](./stdiostreampositionpreference/) | ラッパー作成時に std::basic_iostream とその派生クラスが異なる読み書き位置を持つ場合に、ストリーム内で共通の読み書き位置として好ましい位置を決定します。 |
| [SystemIOStreamWrappingMode](./systemiostreamwrappingmode/) | [System::IO::Stream](./stream/) のようなストリームでラッパーが実行する I/O 操作モードを指定します。 |
## 型エイリアス

| 型エイリアス | 説明 |
| --- | --- |
| [IOException](./ioexception/) |  |
| [EndOfStreamException](./endofstreamexception/) |  |
| [InvalidDataException](./invaliddataexception/) |  |
| [DirectoryNotFoundException](./directorynotfoundexception/) |  |
| [FileLoadException](./fileloadexception/) |  |
| [PathTooLongException](./pathtoolongexception/) |  |
| [DriveNotFoundException](./drivenotfoundexception/) |  |
| [BinaryWriterPtr](./binarywriterptr/) | このクラスへの shared pointer のエイリアスです。 |
| [FileNotFoundException](./filenotfoundexception/) | ディスク上に存在しないファイルにアクセスしようとしたときにスローされる例外です。FileNotFoundException クラスのインスタンスを [System::SmartPtr](../system/smartptr/) でラップしないでください。 |
| [STDIStreamWrapper](./stdistreamwrapper/) | [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) の char 文字型に対する特殊化です。 |
| [STDWIStreamWrapper](./stdwistreamwrapper/) | [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) の **wchar_t** 文字型に対する特殊化です。 |
| [STDOStreamWrapper](./stdostreamwrapper/) | [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) の char 文字型に対する特殊化です。 |
| [STDWOStreamWrapper](./stdwostreamwrapper/) | [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) の **wchar_t** 文字型に対する特殊化です。 |
| [STDIOStreamWrapper](./stdiostreamwrapper/) | [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) の char 文字型に対する特殊化です。 |
| [STDWIOStreamWrapper](./stdwiostreamwrapper/) | [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) の **wchar_t** 文字型に対する特殊化です。 |
| [SystemIStreamWrapper](./systemistreamwrapper/) | [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) の char 文字型に対する特殊化です。 |
| [SystemWIStreamWrapper](./systemwistreamwrapper/) | [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) の **wchar_t** 文字型に対する特殊化です。 |
| [SystemOStreamWrapper](./systemostreamwrapper/) | [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) の char 文字型に対する特殊化です。 |
| [SystemWOStreamWrapper](./systemwostreamwrapper/) | [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) の **wchar_t** 文字型に対する特殊化です。 |
| [SystemIOStreamWrapper](./systemiostreamwrapper/) | [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) の char 文字型に対する特殊化です。 |
| [SystemWIOStreamWrapper](./systemwiostreamwrapper/) | [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) の **wchar_t** 文字型に対する特殊化です。 |