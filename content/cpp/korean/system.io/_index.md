---
title: "System::IO"
second_title: C++용 Aspose.Slides API 레퍼런스
description: 
type: docs
weight: 573
url: /ko/system.io/
---
## 클래스

| 클래스 | 설명 |
| --- | --- |
| [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) | 이 클래스는 [System.IO.Stream](./stream/)와 유사한 std::basic_iostream 및 파생 객체에 대한 래퍼를 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 인스턴스를 생성하거나 operator new를 사용해서는 안 되며, 이는 런타임 오류 및/또는 어설션 오류를 초래합니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 래핑하고 해당 포인터를 인수로 함수에 전달해야 합니다. |
| [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) | 이 클래스는 [System.IO.Stream](./stream/)와 유사한 std::basic_istream 및 파생 객체에 대한 래퍼를 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 인스턴스를 생성하거나 operator new를 사용해서는 안 되며, 이는 런타임 오류 및/또는 어설션 오류를 초래합니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 래핑하고 해당 포인터를 인수로 함수에 전달해야 합니다. |
| [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) | 이 클래스는 [System.IO.Stream](./stream/)와 유사한 std::basic_ostream 및 파생 객체에 대한 래퍼를 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 인스턴스를 생성하거나 operator new를 사용해서는 안 되며, 이는 런타임 오류 및/또는 어설션 오류를 초래합니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 래핑하고 해당 포인터를 인수로 함수에 전달해야 합니다. |
| [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) | [System::IO::Stream](./stream/)와 유사한 스트림을 래핑하는 버퍼를 나타내며, 이를 std::iostream와 유사한 스트림의 내부 버퍼로 사용할 수 있습니다. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) | 내부 버퍼로 [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)를 사용한 std::iostream와 유사한 래퍼를 나타냅니다. |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) | 내부 버퍼로 [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)를 사용한 std::istream와 유사한 래퍼를 나타냅니다. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) | 내부 버퍼로 [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)를 사용한 std::ostream와 유사한 래퍼를 나타냅니다. |
| [BinaryReader](./binaryreader/) | 특정 인코딩으로 기본 데이터 타입을 이진 데이터로 읽는 리더를 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 인스턴스를 생성하거나 operator new를 사용해서는 안 되며, 이는 런타임 오류 및/또는 어설션 오류를 초래합니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 래핑하고 해당 포인터를 인수로 함수에 전달해야 합니다. |
| [BinaryWriter](./binarywriter/) | 기본 타입 값을 바이트 스트림에 쓰는 라이터를 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 인스턴스를 생성하거나 operator new를 사용해서는 안 되며, 이는 런타임 오류 및/또는 어설션 오류를 초래합니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 래핑하고 해당 포인터를 인수로 함수에 전달해야 합니다. |
| [BufferedStream](./bufferedstream/) | 다른 스트림 위에 버퍼링 레이어를 추가합니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 인스턴스를 생성하거나 operator new를 사용해서는 안 되며, 이는 런타임 오류 및/또는 어설션 오류를 초래합니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 래핑하고 해당 포인터를 인수로 함수에 전달해야 합니다. |
| [Details_DirectoryNotFoundException](./details_directorynotfoundexception/) |  |
| [Details_DriveNotFoundException](./details_drivenotfoundexception/) |  |
| [Details_EndOfStreamException](./details_endofstreamexception/) |  |
| [Details_FileLoadException](./details_fileloadexception/) |  |
| [Details_FileNotFoundException](./details_filenotfoundexception/) | 디스크에 존재하지 않는 파일에 접근하려는 시도가 실패했을 때 발생하는 예외입니다. 이 클래스의 인스턴스를 직접 생성하지 마십시오. 대신 FileNotFoundException 클래스를 사용하십시오. FileNotFoundException 클래스 인스턴스를 [System::SmartPtr](../system/smartptr/)에 래핑하지 마십시오. |
| [Details_InvalidDataException](./details_invaliddataexception/) |  |
| [Details_IOException](./details_ioexception/) |  |
| [Details_PathTooLongException](./details_pathtoolongexception/) |  |
| [Directory](./directory/) | 디렉터리를 조작하는 메서드를 포함합니다. 인스턴스 서비스를 제공하지 않는 정적 타입이며, 어떤 방법으로도 인스턴스를 생성해서는 안 됩니다. |
| [DirectoryInfo](./directoryinfo/) | 이 클래스는 파일 시스템 경로와 해당 경로가 가리키는 디렉터리를 나타내며 디렉터리 조작을 위한 인스턴스 메서드를 제공합니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 인스턴스를 생성하거나 operator new를 사용해서는 안 되며, 이는 런타임 오류 및/또는 어설션 오류를 초래합니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 래핑하고 해당 포인터를 인수로 함수에 전달해야 합니다. |
| [File](./file/) | 파일을 조작하는 메서드를 제공합니다. 인스턴스 서비스를 제공하지 않는 정적 타입이며, 어떤 방법으로도 인스턴스를 생성해서는 안 됩니다. |
| [FileInfo](./fileinfo/) | 파일 경로와 해당 파일을 나타내며, 이를 조작하기 위한 메서드를 제공합니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 인스턴스를 생성하거나 operator new를 사용해서는 안 되며, 이는 런타임 오류 및/또는 어설션 오류를 초래합니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 래핑하고 해당 포인터를 인수로 함수에 전달해야 합니다. |
| [FileStream](./filestream/) | 동기 및 비동기 읽기·쓰기 작업을 지원하는 파일 스트림을 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 인스턴스를 생성하거나 operator new를 사용해서는 안 되며, 이는 런타임 오류 및/또는 어설션 오류를 초래합니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 래핑하고 해당 포인터를 인수로 함수에 전달해야 합니다. |
| [FileSystemInfo](./filesysteminfo/) | [FileInfo](./fileinfo/)와 [DirectoryInfo](./directoryinfo/)의 기본 클래스입니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 인스턴스를 생성하거나 operator new를 사용해서는 안 되며, 이는 런타임 오류 및/또는 어설션 오류를 초래합니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 래핑하고 해당 포인터를 인수로 함수에 전달해야 합니다. |
| [FileSystemInfoStat](./filesysteminfostat/) | 파일 또는 디렉터리 정보를 나타냅니다. |
| [MemoryStream](./memorystream/) | 메모리에서 읽고 쓰는 스트림을 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 인스턴스를 생성하거나 operator new를 사용해서는 안 되며, 이는 런타임 오류 및/또는 어설션 오류를 초래합니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 래핑하고 해당 포인터를 인수로 함수에 전달해야 합니다. |
| [Path](./path/) |  |
| [STDIOStreamWrapperBase](./stdiostreamwrapperbase/) | [System.IO.Stream](./stream/)와 유사한 래퍼의 기본 클래스를 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 인스턴스를 생성하거나 operator new를 사용해서는 안 되며, 이는 런타임 오류 및/또는 어설션 오류를 초래합니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 래핑하고 해당 포인터를 인수로 함수에 전달해야 합니다. |
| [Stream](./stream/) | 다양한 스트림 구현을 위한 기본 클래스를 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 인스턴스를 생성하거나 operator new를 사용해서는 안 되며, 이는 런타임 오류 및/또는 어설션 오류를 초래합니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 래핑하고 해당 포인터를 인수로 함수에 전달해야 합니다. |
| [StreamReader](./streamreader/) | 바이트 스트림에서 문자를 읽는 리더를 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 인스턴스를 생성하거나 operator new를 사용해서는 안 되며, 이는 런타임 오류 및/또는 어설션 오류를 초래합니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 래핑하고 해당 포인터를 인수로 함수에 전달해야 합니다. |
| [StreamWriter](./streamwriter/) | 바이트 스트림에 문자를 쓰는 라이터를 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 인스턴스를 생성하거나 operator new를 사용해서는 안 되며, 이는 런타임 오류 및/또는 어설션 오류를 초래합니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 래핑하고 해당 포인터를 인수로 함수에 전달해야 합니다. |
| [StringReader](./stringreader/) | 문자열에서 문자를 읽는 리더를 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 인스턴스를 생성하거나 operator new를 사용해서는 안 되며, 이는 런타임 오류 및/또는 어설션 오류를 초래합니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 래핑하고 해당 포인터를 인수로 함수에 전달해야 합니다. |
| [StringWriter](./stringwriter/) | 문자열에 정보를 쓰는 [TextWriter](./textwriter/)를 구현합니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 인스턴스를 생성하거나 operator new를 사용해서는 안 되며, 이는 런타임 오류 및/또는 어설션 오류를 초래합니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 래핑하고 해당 포인터를 인수로 함수에 전달해야 합니다. |
| [TextReader](./textreader/) | 다양한 소스에서 문자 시퀀스를 읽는 리더를 나타내는 클래스들의 기본 클래스입니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 인스턴스를 생성하거나 operator new를 사용해서는 안 되며, 이는 런타임 오류 및/또는 어설션 오류를 초래합니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 래핑하고 해당 포인터를 인수로 함수에 전달해야 합니다. |
| [TextWriter](./textwriter/) | 다양한 목적지에 문자 시퀀스를 쓰는 라이터를 나타내는 클래스들의 기본 클래스입니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 인스턴스를 생성하거나 operator new를 사용해서는 안 되며, 이는 런타임 오류 및/또는 어설션 오류를 초래합니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 래핑하고 해당 포인터를 인수로 함수에 전달해야 합니다. |
| [UnmanagedMemoryStream](./unmanagedmemorystream/) | 관리되지 않는 메모리에 대한 접근을 제공합니다. 이 클래스의 객체는 [System::MakeObject()](../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 인스턴스를 생성하거나 operator new를 사용해서는 안 되며, 이는 런타임 오류 및/또는 어설션 오류를 초래합니다. 항상 이 클래스를 [System::SmartPtr](../system/smartptr/) 포인터로 래핑하고 해당 포인터를 인수로 함수에 전달해야 합니다. |
## 함수

| 함수 | 설명 |
| --- | --- |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_istream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/)) | std::basic_istream와 유사한 스트림에 대한 래퍼 함수입니다. |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_ostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/)) | std::basic_ostream와 유사한 스트림에 대한 래퍼 함수입니다. |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_iostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/), [STDIOStreamPositionPreference](./stdiostreampositionpreference/)) | std::basic_iostream와 유사한 스트림에 대한 래퍼 함수입니다. |
## 열거형

| 열거형 | 설명 |
| --- | --- |
| [FileAccess](./fileaccess/) | 파일을 열 때 접근 유형을 지정합니다. |
| [FileAttributes](./fileattributes/) | 디렉터리 또는 파일의 속성을 나타냅니다. |
| [FileMode](./filemode/) | 파일을 여는 방법을 지정합니다. |
| [FileOptions](./fileoptions/) | [FileStream](./filestream/) 객체를 생성하기 위한 고급 옵션을 나타냅니다. |
| [FileShare](./fileshare/) | 열리는 파일에 대해 다른 [FileStream](./filestream/) 객체가 가질 수 있는 접근 종류를 지정합니다. |
| [SearchOption](./searchoption/) | 검색을 현재 디렉터리에서만 수행할지, 현재 디렉터리와 모든 하위 디렉터리에서 수행할지를 지정합니다. |
| [SeekOrigin](./seekorigin/) | 스트림에서 기준 위치를 지정하며, 이 기준 위치를 기준으로 이동할 위치를 지정합니다. |
| [STDIOStreamWrappingMode](./stdiostreamwrappingmode/) | 래퍼가 std::iostream와 유사한 스트림에 수행할 I/O 작업 모드를 지정합니다. |
| [STDIOStreamPositionPreference](./stdiostreampositionpreference/) | 래퍼 생성 시점에 std::basic_iostream 및 그 파생 클래스가 서로 다른 읽기·쓰기 위치를 갖는 경우, 공통 읽기·쓰기 위치로 선호되는 스트림 내 위치를 결정합니다. |
| [SystemIOStreamWrappingMode](./systemiostreamwrappingmode/) | 래퍼가 [System::IO::Stream](./stream/)와 유사한 스트림에 수행할 I/O 작업 모드를 지정합니다. |
## 타입별칭

| 타입별칭 | 설명 |
| --- | --- |
| [IOException](./ioexception/) |  |
| [EndOfStreamException](./endofstreamexception/) |  |
| [InvalidDataException](./invaliddataexception/) |  |
| [DirectoryNotFoundException](./directorynotfoundexception/) |  |
| [FileLoadException](./fileloadexception/) |  |
| [PathTooLongException](./pathtoolongexception/) |  |
| [DriveNotFoundException](./drivenotfoundexception/) |  |
| [BinaryWriterPtr](./binarywriterptr/) | 이 클래스에 대한 shared pointer의 별칭입니다. |
| [FileNotFoundException](./filenotfoundexception/) | 디스크에 존재하지 않는 파일에 접근하려는 시도가 실패했을 때 발생하는 예외입니다. FileNotFoundException 클래스 인스턴스를 [System::SmartPtr](../system/smartptr/)에 래핑하지 마십시오. |
| [STDIStreamWrapper](./stdistreamwrapper/) | [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)에 대한 char 문자 유형 특수화. |
| [STDWIStreamWrapper](./stdwistreamwrapper/) | [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)에 대한 **wchar_t** 문자 유형 특수화. |
| [STDOStreamWrapper](./stdostreamwrapper/) | [BasicSTDOStreamWrapper](./basicstdostreamwrapper/)에 대한 char 문자 유형 특수화. |
| [STDWOStreamWrapper](./stdwostreamwrapper/) | [BasicSTDOStreamWrapper](./basicstdostreamwrapper/)에 대한 **wchar_t** 문자 유형 특수화. |
| [STDIOStreamWrapper](./stdiostreamwrapper/) | [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/)에 대한 char 문자 유형 특수화. |
| [STDWIOStreamWrapper](./stdwiostreamwrapper/) | [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/)에 대한 **wchar_t** 문자 유형 특수화. |
| [SystemIStreamWrapper](./systemistreamwrapper/) | [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)에 대한 char 문자 유형 특수화. |
| [SystemWIStreamWrapper](./systemwistreamwrapper/) | [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)에 대한 **wchar_t** 문자 유형 특수화. |
| [SystemOStreamWrapper](./systemostreamwrapper/) | [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)에 대한 char 문자 유형 특수화. |
| [SystemWOStreamWrapper](./systemwostreamwrapper/) | [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)에 대한 **wchar_t** 문자 유형 특수화. |
| [SystemIOStreamWrapper](./systemiostreamwrapper/) | [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)에 대한 char 문자 유형 특수화. |
| [SystemWIOStreamWrapper](./systemwiostreamwrapper/) | [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)에 대한 **wchar_t** 문자 유형 특수화. |