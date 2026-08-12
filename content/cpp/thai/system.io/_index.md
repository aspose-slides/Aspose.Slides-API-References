---
title: "System::IO"
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: 
type: docs
weight: 573
url: /th/system.io/
---
## คลาส

| คลาส | คำอธิบาย |
| --- | --- |
| [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) | เป็นตัวห่อคล้าย [System.IO.Stream](./stream/) สำหรับ std::basic_iostreamและอ็อบเจ็กต์ที่สืบทอดจากมัน. อ็อบเจ็กต์ของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อบกพร่องการตรวจสอบ. ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) | เป็นตัวห่อคล้าย [System.IO.Stream](./stream/) สำหรับ std::basic_istreamและอ็อบเจ็กต์ที่สืบทอดจากมัน. อ็อบเจ็กต์ของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อบกพร่องการตรวจสอบ. ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) | เป็นตัวห่อคล้าย [System.IO.Stream](./stream/) สำหรับ std::basic_ostreamและอ็อบเจ็กต์ที่สืบทอดจากมัน. อ็อบเจ็กต์ของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อบกพร่องการตรวจสอบ. ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) | เป็นบัฟเฟอร์ที่ห่อ [System::IO::Stream](./stream/)-like streamsและทำให้สามารถใช้เป็นบัฟเฟอร์ภายในของสตรีมที่คล้าย std::iostream |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) | เป็นตัวห่อคล้าย std::iostreamที่ใช้ [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) เป็นบัฟเฟอร์ภายใน |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) | เป็นตัวห่อคล้าย std::istreamที่ใช้ [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) เป็นบัฟเฟอร์ภายใน |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) | เป็นตัวห่อคล้าย std::ostreamที่ใช้ [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) เป็นบัฟเฟอร์ภายใน |
| [BinaryReader](./binaryreader/) | เป็นรีเดอร์ที่อ่านข้อมูลชนิดพื้นฐานเป็นข้อมูลไบนารีในรูปแบบการเข้ารหัสที่ระบุ. อ็อบเจ็กต์ของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อบกพร่องการตรวจสอบ. ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [BinaryWriter](./binarywriter/) | เป็นวริตเตอร์ที่เขียนค่าชนิดพื้นฐานลงในไบต์สตรีม. อ็อบเจ็กต์ของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อบกพร่องการตรวจสอบ. ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [BufferedStream](./bufferedstream/) | เพิ่มชั้นบัฟเฟอร์บนสตรีมอื่น. อ็อบเจ็กต์ของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อบกพร่องการตรวจสอบ. ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [Details_DirectoryNotFoundException](./details_directorynotfoundexception/) |  |
| [Details_DriveNotFoundException](./details_drivenotfoundexception/) |  |
| [Details_EndOfStreamException](./details_endofstreamexception/) |  |
| [Details_FileLoadException](./details_fileloadexception/) |  |
| [Details_FileNotFoundException](./details_filenotfoundexception/) | ข้อยกเว้นที่ถูกโยนเมื่อพยายามเข้าถึงไฟล์ที่ไม่มีอยู่บนดิสก์ล้มเหลว. อย่าสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส FileNotFoundException แทน. อย่าห่ออินสแตนซ์ของคลาส FileNotFoundException เข้าใน [System::SmartPtr](../system/smartptr/). |
| [Details_InvalidDataException](./details_invaliddataexception/) |  |
| [Details_IOException](./details_ioexception/) |  |
| [Details_PathTooLongException](./details_pathtoolongexception/) |  |
| [Directory](./directory/) | มีเมธอดสำหรับจัดการไดเรกทอรี. นี่เป็นประเภทแบบสแตติกที่ไม่มีบริการอินสแตนซ์. ไม่ควรสร้างอินสแตนซ์ของมันโดยวิธีใด ๆ |
| [DirectoryInfo](./directoryinfo/) | เป็นเส้นทางระบบไฟล์, ไดเรกทอรีที่อ้างอิงโดยเส้นทางนี้และให้เมธอดอินสแตนซ์สำหรับจัดการไดเรกทอรี. อ็อบเจ็กต์ของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อบกพร่องการตรวจสอบ. ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [File](./file/) | มีเมธอดสำหรับจัดการไฟล์. นี่เป็นประเภทแบบสแตติกที่ไม่มีบริการอินสแตนซ์. ไม่ควรสร้างอินสแตนซ์ของมันโดยวิธีใด ๆ |
| [FileInfo](./fileinfo/) | เป็นเส้นทางไปยังไฟล์และไฟล์ที่อ้างอิงโดยเส้นทางนี้และให้เมธอดสำหรับจัดการมัน. อ็อบเจ็กต์ของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อบกพร่องการตรวจสอบ. ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [FileStream](./filestream/) | เป็นสตรีมไฟล์ที่รองรับการอ่านและเขียนแบบซิงโครนัสและอะซิงโครนัส. อ็อบเจ็กต์ของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อบกพร่องการตรวจสอบ. ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [FileSystemInfo](./filesysteminfo/) | คลาสฐานสำหรับ [FileInfo](./fileinfo/)และ[DirectoryInfo](./directoryinfo/). อ็อบเจ็กต์ของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อบกพร่องการตรวจสอบ. ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [FileSystemInfoStat](./filesysteminfostat/) | แสดงข้อมูลเกี่ยวกับไฟล์หรือไดเรกทอรี |
| [MemoryStream](./memorystream/) | เป็นสตรีมที่อ่านและเขียนจากหน่วยความจำ. อ็อบเจ็กต์ของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อบกพร่องการตรวจสอบ. ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [Path](./path/) | มีเมธอดสำหรับจัดการเส้นทาง. นี่เป็นประเภทแบบสแตติกที่ไม่มีบริการอินสแตนซ์. ไม่ควรสร้างอินสแตนซ์ของมันโดยวิธีใด ๆ |
| [STDIOStreamWrapperBase](./stdiostreamwrapperbase/) | เป็นคลาสฐานสำหรับตัวห่อคล้าย [System.IO.Stream](./stream/). อ็อบเจ็กต์ของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อบกพร่องการตรวจสอบ. ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [Stream](./stream/) | คลาสฐานสำหรับการนำไปใช้ของสตรีมหลากหลายรูปแบบ. อ็อบเจ็กต์ของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อบกพร่องการตรวจสอบ. ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [StreamReader](./streamreader/) | เป็นรีเดอร์ที่อ่านอักขระจากไบต์สตรีม. อ็อบเจ็กต์ของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อบกพร่องการตรวจสอบ. ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [StreamWriter](./streamwriter/) | เป็นวริตเตอร์ที่เขียนอักขระลงในไบต์สตรีม. อ็อบเจ็กต์ของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อบกพร่องการตรวจสอบ. ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [StringReader](./stringreader/) | เป็นรีเดอร์ที่อ่านอักขระจากสตริง. อ็อบเจ็กต์ของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อบกพร่องการตรวจสอบ. ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [StringWriter](./stringwriter/) | ใช้ [TextWriter](./textwriter/) ที่เขียนข้อมูลลงในสตริง. อ็อบเจ็กต์ของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อบกพร่องการตรวจสอบ. ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [TextReader](./textreader/) | คลาสฐานสำหรับคลาสที่เป็นรีเดอร์อ่านลำดับอักขระจากแหล่งที่มาต่าง ๆ. อ็อบเจ็กต์ของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อบกพร่องการตรวจสอบ. ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [TextWriter](./textwriter/) | คลาสฐานสำหรับคลาสที่เป็นวริตเตอร์เขียนลำดับอักขระไปยังปลายทางต่าง ๆ. อ็อบเจ็กต์ของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อบกพร่องการตรวจสอบ. ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
| [UnmanagedMemoryStream](./unmanagedmemorystream/) | ให้การเข้าถึงหน่วยความจำที่ไม่ได้จัดการ. อ็อบเจ็กต์ของคลาสนี้ควรได้รับการจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อบกพร่องการตรวจสอบ. ควรห่อคลาสนี้เข้าในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์. |
## ฟังก์ชัน

| ฟังก์ชัน | คำอธิบาย |
| --- | --- |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_istream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/)) | ฟังก์ชันห่อสำหรับสตรีมที่คล้าย std::basic_istream |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_ostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/)) | ฟังก์ชันห่อสำหรับสตรีมที่คล้าย std::basic_ostream |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_iostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/), [STDIOStreamPositionPreference](./stdiostreampositionpreference/)) | ฟังก์ชันห่อสำหรับสตรีมที่คล้าย std::basic_iostream |
## Enum

| Enum | คำอธิบาย |
| --- | --- |
| [FileAccess](./fileaccess/) | ระบุประเภทการเข้าถึงเมื่อเปิดไฟล์ |
| [FileAttributes](./fileattributes/) | แสดงคุณลักษณะของไดเรกทอรีหรือไฟล์ |
| [FileMode](./filemode/) | ระบุวิธีการเปิดไฟล์ |
| [FileOptions](./fileoptions/) | แสดงตัวเลือกขั้นสูงสำหรับการสร้างอ็อบเจ็กต์ [FileStream](./filestream/) |
| [FileShare](./fileshare/) | ระบุว่าชนิดการเข้าถึงใดที่ออบเจ็กต์ [FileStream](./filestream/) อื่น ๆ สามารถมีต่อไฟล์ที่กำลังเปิด |
| [SearchOption](./searchoption/) | ระบุว่าการค้นหาควรทำเฉพาะในไดเรกทอรีปัจจุบัน หรือในไดเรกทอรีปัจจุบันและทุกไดเรกทอรีย่อย |
| [SeekOrigin](./seekorigin/) | ระบุตำแหน่งอ้างอิงในสตรีมที่ตำแหน่งที่ต้องการเลื่อนไปอิงตาม |
| [STDIOStreamWrappingMode](./stdiostreamwrappingmode/) | ระบุโหมดของการทำ I/O ที่ห่อจะดำเนินการบนสตรีมที่คล้าย std::iostream |
| [STDIOStreamPositionPreference](./stdiostreampositionpreference/) | กำหนดว่าตำแหน่งใดในสตรีมที่ควรเป็นตำแหน่งอ่าน-เขียนร่วมเมื่อ std::basic_iostreamและคลาสสืบทอดมีตำแหน่งอ่านและเขียนที่แตกต่างกันในขณะที่สร้างห่อ |
| [SystemIOStreamWrappingMode](./systemiostreamwrappingmode/) | ระบุโหมดของการทำ I/O ที่ห่อจะดำเนินการบนสตรีมที่คล้าย [System::IO::Stream](./stream/) |
## Typedef

| Typedef | คำอธิบาย |
| --- | --- |
| [IOException](./ioexception/) |  |
| [EndOfStreamException](./endofstreamexception/) |  |
| [InvalidDataException](./invaliddataexception/) |  |
| [DirectoryNotFoundException](./directorynotfoundexception/) |  |
| [FileLoadException](./fileloadexception/) |  |
| [PathTooLongException](./pathtoolongexception/) |  |
| [DriveNotFoundException](./drivenotfoundexception/) |  |
| [BinaryWriterPtr](./binarywriterptr/) | นามแฝงสำหรับ shared pointer ไปยังคลาสนี้ |
| [FileNotFoundException](./filenotfoundexception/) | ข้อยกเว้นที่ถูกโยนเมื่อพยายามเข้าถึงไฟล์ที่ไม่มีอยู่บนดิสก์ล้มเหลว. อย่าห่ออินสแตนซ์ของคลาส FileNotFoundException เข้าใน [System::SmartPtr](../system/smartptr/). |
| [STDIStreamWrapper](./stdistreamwrapper/) | การเฉพาะสำหรับ [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) สำหรับชนิดอักขระ char |
| [STDWIStreamWrapper](./stdwistreamwrapper/) | การเฉพาะสำหรับ [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) สำหรับชนิดอักขระ **wchar_t** |
| [STDOStreamWrapper](./stdostreamwrapper/) | การเฉพาะสำหรับ [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) สำหรับชนิดอักขระ char |
| [STDWOStreamWrapper](./stdwostreamwrapper/) | การเฉพาะสำหรับ [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) สำหรับชนิดอักขระ **wchar_t** |
| [STDIOStreamWrapper](./stdiostreamwrapper/) | การเฉพาะสำหรับ [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) สำหรับชนิดอักขระ char |
| [STDWIOStreamWrapper](./stdwiostreamwrapper/) | การเฉพาะสำหรับ [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) สำหรับชนิดอักขระ **wchar_t** |
| [SystemIStreamWrapper](./systemistreamwrapper/) | การเฉพาะสำหรับ [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) สำหรับชนิดอักขระ char |
| [SystemWIStreamWrapper](./systemwistreamwrapper/) | การเฉพาะสำหรับ [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) สำหรับชนิดอักขระ **wchar_t** |
| [SystemOStreamWrapper](./systemostreamwrapper/) | การเฉพาะสำหรับ [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) สำหรับชนิดอักขระ char |
| [SystemWOStreamWrapper](./systemwostreamwrapper/) | การเฉพาะสำหรับ [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) สำหรับชนิดอักขระ **wchar_t** |
| [SystemIOStreamWrapper](./systemiostreamwrapper/) | การเฉพาะสำหรับ [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) สำหรับชนิดอักขระ char |
| [SystemWIOStreamWrapper](./systemwiostreamwrapper/) | การเฉพาะสำหรับ [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) สำหรับชนิดอักขระ **wchar_t** |