---
title: "System::IO"
second_title: Aspose.Slides for C++ API Referansı
description: 
type: docs
weight: 573
url: /tr/system.io/
---
## Sınıflar

| Sınıf | Açıklama |
| --- | --- |
| [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) | [System.IO.Stream](./stream/)-benzeri bir std::basic_iostream ve türetilmiş nesneler için sarmalayıcı temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığında veya operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Her zaman bu sınıfı [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) | [System.IO.Stream](./stream/)-benzeri bir std::basic_istream ve türetilmiş nesneler için sarmalayıcı temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığında veya operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Her zaman bu sınıfı [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) | [System.IO.Stream](./stream/)-benzeri bir std::basic_ostream ve türetilmiş nesneler için sarmalayıcı temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığında veya operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Her zaman bu sınıfı [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) | [System::IO::Stream](./stream/)-benzeri akışları saran bir tampon temsil eder ve bunların std::iostream-benzeri akışların dahili tamponu olarak kullanılmasına izin verir. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) | [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)'yi dahili tampon olarak kullanan bir std::iostream-benzeri sarmalayıcı temsil eder. |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) | [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)'yi dahili tampon olarak kullanan bir std::istream-benzeri sarmalayıcı temsil eder. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) | [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)'yi dahili tampon olarak kullanan bir std::ostream-benzeri sarmalayıcı temsil eder. |
| [BinaryReader](./binaryreader/) | Belirli bir kodlamada ilkel veri türlerini ikili veri olarak okuyan bir okuyucu temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığında veya operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Her zaman bu sınıfı [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [BinaryWriter](./binarywriter/) | Bir bayt akışına ilkel türlerin değerlerini yazan bir yazar temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığında veya operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Her zaman bu sınıfı [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [BufferedStream](./bufferedstream/) | Başka bir akışın üzerine bir tamponlama katmanı ekler. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığında veya operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Her zaman bu sınıfı [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [Details_DirectoryNotFoundException](./details_directorynotfoundexception/) |  |
| [Details_DriveNotFoundException](./details_drivenotfoundexception/) |  |
| [Details_EndOfStreamException](./details_endofstreamexception/) |  |
| [Details_FileLoadException](./details_fileloadexception/) |  |
| [Details_FileNotFoundException](./details_filenotfoundexception/) | Diskte mevcut olmayan bir dosyaya erişim girişimi başarısız olduğunda fırlatılan istisna. Bu sınıfın örneklerini manuel olarak oluşturmamalısınız. Bunun yerine FileNotFoundException sınıfını kullanın. FileNotFoundException sınıfı örneklerini [System::SmartPtr](../system/smartptr/) içine sarmamalısınız. |
| [Details_InvalidDataException](./details_invaliddataexception/) |  |
| [Details_IOException](./details_ioexception/) |  |
| [Details_PathTooLongException](./details_pathtoolongexception/) |  |
| [Directory](./directory/) | Dizinleri işlemek için yöntemler içerir. Bu, örnek hizmeti olmayan statik bir türdür. Herhangi bir şekilde örneklerini oluşturmayın. |
| [DirectoryInfo](./directoryinfo/) | Bu sınıf bir dosya sistemi yolunu, bu yolla belirtilen dizini temsil eder ve dizinleri işlemek için örnek yöntemler sağlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığında veya operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Her zaman bu sınıfı [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [File](./file/) | Dosyaları işlemek için yöntemler sağlar. Bu, örnek hizmeti olmayan statik bir türdür. Herhangi bir şekilde örneklerini oluşturmayın. |
| [FileInfo](./fileinfo/) | Bir dosyaya giden yolu ve bu dosyayı temsil eder ve onu işlemek için yöntemler sağlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığında veya operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Her zaman bu sınıfı [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [FileStream](./filestream/) | Eşzamanlı ve eşzamansız okuma ve yazma işlemlerini destekleyen bir dosya akışı temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığında veya operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Her zaman bu sınıfı [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [FileSystemInfo](./filesysteminfo/) | [FileInfo](./fileinfo/) ve [DirectoryInfo](./directoryinfo/) için temel sınıf. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığında veya operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Her zaman bu sınıfı [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [FileSystemInfoStat](./filesysteminfostat/) | Bir dosya veya dizin hakkındaki bilgileri temsil eder. |
| [MemoryStream](./memorystream/) | Bellekten okuyan ve belleğe yazan bir akış temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığında veya operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Her zaman bu sınıfı [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [Path](./path/) | Yolları işlemek için yöntemler sağlar. Bu, örnek hizmeti olmayan statik bir türdür. Herhangi bir şekilde örneklerini oluşturmayın. |
| [STDIOStreamWrapperBase](./stdiostreamwrapperbase/) | [System.IO.Stream](./stream/)-benzeri sarmalayıcılar için temel sınıf. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığında veya operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Her zaman bu sınıfı [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [Stream](./stream/) | Çeşitli akış gerçekleştirmeleri için temel sınıf. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığında veya operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Her zaman bu sınıfı [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [StreamReader](./streamreader/) | Bir bayt akışından karakter okuyan bir okuyucu temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığında veya operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Her zaman bu sınıfı [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [StreamWriter](./streamwriter/) | Bir bayt akışına karakter yazan bir yazar temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığında veya operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Her zaman bu sınıfı [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [StringReader](./stringreader/) | Bir dizeden karakter okuyan bir okuyucu temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığında veya operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Her zaman bu sınıfı [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [StringWriter](./stringwriter/) | [TextWriter](./textwriter/)'yi uygulayan ve bilgileri bir dizeye yazan bir sınıf. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığında veya operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Her zaman bu sınıfı [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [TextReader](./textreader/) | Farklı kaynaklardan karakter dizileri okuyan okuyucuları temsil eden sınıflar için temel sınıf. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığında veya operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Her zaman bu sınıfı [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [TextWriter](./textwriter/) | Farklı hedeflere karakter dizileri yazan yazarları temsil eden sınıflar için temel sınıf. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığında veya operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Her zaman bu sınıfı [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [UnmanagedMemoryStream](./unmanagedmemorystream/) | Yönetilmeyen belleğe erişim sağlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığında veya operator new kullanılarak oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Her zaman bu sınıfı [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
## Fonksiyonlar

| Fonksiyon | Açıklama |
| --- | --- |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_istream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/)) | std::basic_istream-benzeri akışlar için sarmalayıcı işlev. |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_ostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/)) | std::basic_ostream-benzeri akışlar için sarmalayıcı işlev. |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_iostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/), [STDIOStreamPositionPreference](./stdiostreampositionpreference/)) | std::basic_iostream-benzeri akışlar için sarmalayıcı işlev. |
## Enumlar

| Enum | Açıklama |
| --- | --- |
| [FileAccess](./fileaccess/) | Dosya açılırken erişim türünü belirtir. |
| [FileAttributes](./fileattributes/) | Bir dizin veya dosyanın özniteliklerini temsil eder. |
| [FileMode](./filemode/) | Bir dosyanın nasıl açılacağını belirtir. |
| [FileOptions](./fileoptions/) | [FileStream](./filestream/) nesnesi oluşturmak için gelişmiş seçenekleri temsil eder. |
| [FileShare](./fileshare/) | Açılan bir dosyaya diğer [FileStream](./filestream/) nesnelerinin hangi tür erişime sahip olabileceğini belirtir. |
| [SearchOption](./searchoption/) | Aramanın yalnızca geçerli dizinde mi yoksa geçerli dizin ve tüm alt dizinlerde mi yapılacağını belirtir. |
| [SeekOrigin](./seekorigin/) | Arama konumunun belirtileceği akıştaki referans konumunu tanımlar. |
| [STDIOStreamWrappingMode](./stdiostreamwrappingmode/) | Sarmalayıcıların std::iostream-benzeri akışlarda gerçekleştireceği G/Ç işlem modunu belirtir. |
| [STDIOStreamPositionPreference](./stdiostreampositionpreference/) | std::basic_iostream ve türevlerinin farklı okuma ve yazma konumları olduğunda ortak bir okuma-yazma konumu olarak hangi konumun tercih edileceğini belirler. |
| [SystemIOStreamWrappingMode](./systemiostreamwrappingmode/) | Sarmalayıcıların [System::IO::Stream](./stream/)-benzeri akışlarda gerçekleştireceği G/Ç işlem modunu belirtir. |
## Typedef'ler

| Typedef | Açıklama |
| --- | --- |
| [IOException](./ioexception/) |  |
| [EndOfStreamException](./endofstreamexception/) |  |
| [InvalidDataException](./invaliddataexception/) |  |
| [DirectoryNotFoundException](./directorynotfoundexception/) |  |
| [FileLoadException](./fileloadexception/) |  |
| [PathTooLongException](./pathtoolongexception/) |  |
| [DriveNotFoundException](./drivenotfoundexception/) |  |
| [BinaryWriterPtr](./binarywriterptr/) | Bu sınıfa ortak bir işaretçi için bir takma ad. |
| [FileNotFoundException](./filenotfoundexception/) | Diskte mevcut olmayan bir dosyaya erişim girişimi başarısız olduğunda fırlatılan istisna. FileNotFoundException sınıfı örneklerini [System::SmartPtr](../system/smartptr/) içine sarmamalısınız. |
| [STDIStreamWrapper](./stdistreamwrapper/) | char karakter türleri için [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) özelleştirmeleri. |
| [STDWIStreamWrapper](./stdwistreamwrapper/) | **wchar_t** karakter türleri için [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) özelleştirmeleri. |
| [STDOStreamWrapper](./stdostreamwrapper/) | char karakter türleri için [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) özelleştirmeleri. |
| [STDWOStreamWrapper](./stdwostreamwrapper/) | **wchar_t** karakter türleri için [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) özelleştirmeleri. |
| [STDIOStreamWrapper](./stdiostreamwrapper/) | char karakter türleri için [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) özelleştirmeleri. |
| [STDWIOStreamWrapper](./stdwiostreamwrapper/) | **wchar_t** karakter türleri için [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) özelleştirmeleri. |
| [SystemIStreamWrapper](./systemistreamwrapper/) | char karakter türleri için [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) özelleştirmeleri. |
| [SystemWIStreamWrapper](./systemwistreamwrapper/) | **wchar_t** karakter türleri için [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) özelleştirmeleri. |
| [SystemOStreamWrapper](./systemostreamwrapper/) | char karakter türleri için [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) özelleştirmeleri. |
| [SystemWOStreamWrapper](./systemwostreamwrapper/) | **wchar_t** karakter türleri için [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) özelleştirmeleri. |
| [SystemIOStreamWrapper](./systemiostreamwrapper/) | char karakter türleri için [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) özelleştirmeleri. |
| [SystemWIOStreamWrapper](./systemwiostreamwrapper/) | **wchar_t** karakter türleri için [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) özelleştirmeleri. |