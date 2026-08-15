---
title: "System::IO"
second_title: "Aspose.Slides for C++ API 參考"
description: 
type: docs
weight: 573
url: /zh-hant/system.io/
---
## 類別

| 類別 | 描述 |
| --- | --- |
| [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) | 代表一個 [System.IO.Stream](./stream/)-like 包裝器，適用於 std::basic_iostream 及其衍生物件。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) | 代表一個 [System.IO.Stream](./stream/)-like 包裝器，適用於 std::basic_istream 及其衍生物件。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) | 代表一個 [System.IO.Stream](./stream/)-like 包裝器，適用於 std::basic_ostream 及其衍生物件。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) | 代表一個緩衝區，將 [System::IO::Stream](./stream/)-like 串流包裝起來，並允許它們作為 std::iostream-like 串流的內部緩衝區使用。 |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) | 代表一個 std::iostream-like 包裝器，使用 [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) 作為內部緩衝區。 |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) | 代表一個 std::istream-like 包裝器，使用 [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) 作為內部緩衝區。 |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) | 代表一個 std::ostream-like 包裝器，使用 [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) 作為內部緩衝區。 |
| [BinaryReader](./binaryreader/) | 代表一個讀取器，將原始資料型別依特定編碼讀取為二進位資料。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [BinaryWriter](./binarywriter/) | 代表一個寫入器，將原始型別的值寫入位元組串流。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [BufferedStream](./bufferedstream/) | 在另一個串流之上加入緩衝層。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [Details_DirectoryNotFoundException](./details_directorynotfoundexception/) |  |
| [Details_DriveNotFoundException](./details_drivenotfoundexception/) |  |
| [Details_EndOfStreamException](./details_endofstreamexception/) |  |
| [Details_FileLoadException](./details_fileloadexception/) |  |
| [Details_FileNotFoundException](./details_filenotfoundexception/) | 當嘗試存取磁碟上不存在的檔案失敗時拋出的例外。切勿手動建立此類別的實例，請改用 FileNotFoundException 類別。切勿將 FileNotFoundException 類別的實例包裝成 [System::SmartPtr](../system/smartptr/)。 |
| [Details_InvalidDataException](./details_invaliddataexception/) |  |
| [Details_IOException](./details_ioexception/) |  |
| [Details_PathTooLongException](./details_pathtoolongexception/) |  |
| [Directory](./directory/) | 包含操作目錄的方法。這是一個靜態類型，沒有實例服務。絕不要以任何方式建立它的實例。 |
| [DirectoryInfo](./directoryinfo/) | 代表一個檔案系統路徑、由此路徑參照的目錄，並提供操作目錄的實例方法。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [File](./file/) | 提供操作檔案的方法。這是一個靜態類型，沒有實例服務。絕不要以任何方式建立它的實例。 |
| [FileInfo](./fileinfo/) | 代表一個指向檔案的路徑及該檔案，並提供操作該檔案的方法。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [FileStream](./filestream/) | 代表一個支援同步與非同步讀寫操作的檔案串流。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [FileSystemInfo](./filesysteminfo/) | [FileInfo](./fileinfo/) 與 [DirectoryInfo](./directoryinfo/) 的基礎類別。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [FileSystemInfoStat](./filesysteminfostat/) | 代表關於檔案或目錄的資訊。 |
| [MemoryStream](./memorystream/) | 代表一個可從記憶體讀取與寫入的串流。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [Path](./path/) | 提供操作路徑的方法。這是一個靜態類型，沒有實例服務。絕不要以任何方式建立它的實例。 |
| [STDIOStreamWrapperBase](./stdiostreamwrapperbase/) | 代表 [System.IO.Stream](./stream/)-like 包裝器的基礎類別。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [Stream](./stream/) | 各種串流實作的基礎類別。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [StreamReader](./streamreader/) | 代表一個從位元組串流讀取字元的讀取器。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [StreamWriter](./streamwriter/) | 代表一個向位元組串流寫入字元的寫入器。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [StringReader](./stringreader/) | 代表一個從字串讀取字元的讀取器。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [StringWriter](./stringwriter/) | 實作一個將資訊寫入字串的 [TextWriter](./textwriter/)。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [TextReader](./textreader/) | 用於表示從不同來源讀取字元序列的讀取器類別的基礎類別。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [TextWriter](./textwriter/) | 用於表示向不同目的地寫入字元序列的寫入器類別的基礎類別。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |
| [UnmanagedMemoryStream](./unmanagedmemorystream/) | 提供對非受控記憶體的存取。此類別的物件應僅透過 [System::MakeObject()](../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 |

## 函式

| 函式 | 描述 |
| --- | --- |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_istream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/)) | 適用於 std::basic_istream-like 串流的包裝函式。 |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_ostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/)) | 適用於 std::basic_ostream-like 串流的包裝函式。 |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_iostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/), [STDIOStreamPositionPreference](./stdiostreampositionpreference/)) | 適用於 std::basic_iostream-like 串流的包裝函式。 |

## 列舉

| 列舉 | 描述 |
| --- | --- |
| [FileAccess](./fileaccess/) | 指定開啟檔案時的存取類型。 |
| [FileAttributes](./fileattributes/) | 代表目錄或檔案的屬性。 |
| [FileMode](./filemode/) | 指定檔案的開啟方式。 |
| [FileOptions](./fileoptions/) | 代表建立 [FileStream](./filestream/) 物件的進階選項。 |
| [FileShare](./fileshare/) | 指定其他 [FileStream](./filestream/) 物件對被開啟檔案可擁有的存取類型。 |
| [SearchOption](./searchoption/) | 指定搜尋僅在目前目錄，或在目前目錄及其所有子目錄中執行。 |
| [SeekOrigin](./seekorigin/) | 指定在串流中作為參考位置的點，以此為基礎指定要搜尋到的位置。 |
| [STDIOStreamWrappingMode](./stdiostreamwrappingmode/) | 指定包裝器在 std::iostreams-like 串流上執行的 I/O 操作模式。 |
| [STDIOStreamPositionPreference](./stdiostreampositionpreference/) | 當 std::basic_iostream 及其衍生類別在建立包裝器時具有不同的讀寫位置時，決定哪個位置在串流中較適合作為共用的讀寫位置。 |
| [SystemIOStreamWrappingMode](./systemiostreamwrappingmode/) | 指定包裝器在 [System::IO::Stream](./stream/)-like 串流上執行的 I/O 操作模式。 |

## 型別別名

| 型別別名 | 描述 |
| --- | --- |
| [IOException](./ioexception/) |  |
| [EndOfStreamException](./endofstreamexception/) |  |
| [InvalidDataException](./invaliddataexception/) |  |
| [DirectoryNotFoundException](./directorynotfoundexception/) |  |
| [FileLoadException](./fileloadexception/) |  |
| [PathTooLongException](./pathtoolongexception/) |  |
| [DriveNotFoundException](./drivenotfoundexception/) |  |
| [BinaryWriterPtr](./binarywriterptr/) | 此類別的共享指標別名。 |
| [FileNotFoundException](./filenotfoundexception/) | 當嘗試存取磁碟上不存在的檔案失敗時拋出的例外。切勿將 FileNotFoundException 類別的實例包裝成 [System::SmartPtr](../system/smartptr/)。 |
| [STDIStreamWrapper](./stdistreamwrapper/) | 針對 char 字元類型的 [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) 特化。 |
| [STDWIStreamWrapper](./stdwistreamwrapper/) | 針對 **wchar_t** 字元類型的 [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) 特化。 |
| [STDOStreamWrapper](./stdostreamwrapper/) | 針對 char 字元類型的 [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) 特化。 |
| [STDWOStreamWrapper](./stdwostreamwrapper/) | 針對 **wchar_t** 字元類型的 [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) 特化。 |
| [STDIOStreamWrapper](./stdiostreamwrapper/) | 針對 char 字元類型的 [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) 特化。 |
| [STDWIOStreamWrapper](./stdwiostreamwrapper/) | 針對 **wchar_t** 字元類型的 [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) 特化。 |
| [SystemIStreamWrapper](./systemistreamwrapper/) | 針對 char 字元類型的 [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) 特化。 |
| [SystemWIStreamWrapper](./systemwistreamwrapper/) | 針對 **wchar_t** 字元類型的 [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) 特化。 |
| [SystemOStreamWrapper](./systemostreamwrapper/) | 針對 char 字元類型的 [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) 特化。 |
| [SystemWOStreamWrapper](./systemwostreamwrapper/) | 針對 **wchar_t** 字元類型的 [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) 特化。 |
| [SystemIOStreamWrapper](./systemiostreamwrapper/) | 針對 char 字元類型的 [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) 特化。 |
| [SystemWIOStreamWrapper](./systemwiostreamwrapper/) | 針對 **wchar_t** 字元類型的 [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) 特化。 |