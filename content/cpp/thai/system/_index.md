---
title: System
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: 
type: docs
weight: 274
url: /th/system/
---
## คลาส

| คลาส | คำอธิบาย |
| --- | --- |
| [Activator](./activator/) | มีเมธอดสำหรับสร้างประเภทของอ็อบเจ็กต์ |
| [Array](./array/) | คลาสที่เป็นตัวแทนของโครงสร้างข้อมูลแอร์เรย์ อ็อบเจ็กต์ของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeArray()](./makearray/) และ [System::MakeObject()](./makeobject/) เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแต็กหรือใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบ ควรห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](./smartptr/) แล้วใช้ตัวชี้นี้ส่งให้ฟังก์ชันเป็นอาร์กิวเมนต์ |
| [ArrayBase](./arraybase/) | ตัวดัมมี่สำหรับคลาส [System.Array](./array/) (คลาสฐานแบบแอบสเตรคต์สำหรับแอร์เรย์ทั้งหมด) สามารถเติมฟังก์ชันการทำงานตามคำขอได้ |
| [ArraySegment](./arraysegment/) | แสดงส่วนของแอร์เรย์หนึ่งมิติ ประเภทนี้ควรจัดสรรบนสแต็กและส่งให้ฟังก์ชันโดยค่า หรือโดยอ้างอิง ไม่ควรใช้คลาส [System::SmartPtr](./smartptr/) เพื่อจัดการอ็อบเจ็กต์ประเภทนี้ |
| [Attribute](./attribute/) | คลาสฐานสำหรับแอตทริบิวต์ที่กำหนดเอง อ็อบเจ็กต์ของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](./makeobject/) เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแต็กหรือใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบ ควรห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](./smartptr/) แล้วใช้ตัวชี้นี้ส่งให้ฟังก์ชันเป็นอาร์กิวเมนต์ |
| [BitConverter](./bitconverter/) | มีเมธอดที่ทำการแปลงลำดับของไบต์เป็นประเภทค่าและกลับกัน นี้เป็นประเภทแบบสแตติกไม่มีบริการอินสแตนซ์ ไม่ควรสร้างอินสแตนซ์ใด ๆ ของมัน |
| [Boolean](./boolean/) | คลาสที่เก็บสมาชิกสแตติกของประเภท [System.Boolean](./boolean/) .[Net](../system.net/) |
| [BoxedEnum](./boxedenum/) | แสดงค่าการ enum ที่บ็อกซ์อ็อบเจ็กต์ของคลาสนี้ควรจัดสรรด้วยฟังก์ชัน [System::MakeObject()](./makeobject/) เท่านั้น ไม่ควรสร้างอินสแตนซ์บนสแต็กหรือใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบ ควรห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](./smartptr/) แล้วใช้ตัวชี้นี้ส่งให้ฟังก์ชันเป็นอาร์กิวเมนต์ |
| [BoxedValue](./boxedvalue/) | แสดงค่าแบบบ็อกซ์ อ็อบเจ็กต์ของคลาสนี้ควรจัดสรรด้วยฟังก์ชัน [System::MakeObject()](./makeobject/) เท่านั้น ไม่ควรสร้างอินสแตนซ์บนสแต็กหรือใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบ ควรห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](./smartptr/) แล้วใช้ตัวชี้นี้ส่งให้ฟังก์ชันเป็นอาร์กิวเมนต์ |
| [BoxedValue< ValueTuple< Args... > >](./boxedvalue_tmpl_valuetuple_tmpl_args_dots__end_tmpl__end_tmpl/) | เวอร์ชันบ็อกซ์ของ value tuple |
| [BoxedValueBase](./boxedvaluebase/) | คลาสฐานที่กำหนดอินเทอร์เฟซและทำการนำเมธอดพื้นฐานบางอย่างของคลาสลูกที่เป็นค่าบ็อกซ์ อ็อบเจ็กต์ของคลาสนี้ควรจัดสรรด้วยฟังก์ชัน [System::MakeObject()](./makeobject/) เท่านั้น ไม่ควรสร้างอินสแตนซ์บนสแต็กหรือใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบ ควรห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](./smartptr/) แล้วใช้ตัวชี้นี้ส่งให้ฟังก์ชันเป็นอาร์กิวเมนต์ |
| [Buffer](./buffer/) | มีเมธอดที่จัดการแอร์เรย์ไบต์ดิบ นี้เป็นประเภทแบบสแตติกไม่มีบริการอินสแตนซ์ ไม่ควรสร้างอินสแตนซ์ใด ๆ ของมัน |
| [Byte](./byte/) | มีเมธอดสำหรับทำงานกับจำนวนเต็มบิตไม่มีเครื่องหมาย 8-bit |
| [Char](./char/) | มีเมธอดสำหรับจัดการอักขระที่แทนเป็นหน่วยรหัส UTF-16 นี้เป็นประเภทแบบสแตติกไม่มีบริการอินสแตนซ์ ไม่ควรสร้างอินสแตนซ์ใด ๆ ของมัน |
| [Comparison](./comparison/) | แสดงตัวชี้ไปยังเมธอดที่เปรียบเทียบอ็อบเจ็กต์สองตัวของประเภทเดียวกัน ประเภทนี้ควรจัดสรรบนสแต็กและส่งให้ฟังก์ชันโดยค่า หรือโดยอ้างอิง ไม่ควรใช้คลาส [System::SmartPtr](./smartptr/) เพื่อจัดการอ็อบเจ็กต์ประเภทนี้ |
| [Console](./console/) | มีเมธอดสำหรับส่งออกข้อมูลไปยังสตรีมเอาต์พุตมาตรฐาน นี้เป็นประเภทแบบสแตติกไม่มีบริการอินสแตนซ์ ไม่ควรสร้างอินสแตนซ์ใด ๆ ของมัน |
| [ConsoleOutput](./consoleoutput/) | แสดงสตรีมเอาต์พุตมาตรฐาน อ็อบเจ็กต์ของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](./makeobject/) เท่านั้น ไม่ควรสร้างอินสแตนซ์บนสแต็กหรือใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบ ควรห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](./smartptr/) แล้วใช้ตัวชี้นี้ส่งให้ฟังก์ชันเป็นอาร์กิวเมนต์ |
| [DateTime](./datetime/) | แสดงค่าที่ระบุวันที่และเวลาในต่อเนื่องของเวลา ประเภทนี้ควรจัดสรรบนสแต็กและส่งให้ฟังก์ชันโดยค่า หรือโดยอ้างอิง ไม่ควรใช้คลาส [System::SmartPtr](./smartptr/) เพื่อจัดการอ็อบเจ็กต์ประเภทนี้ |
| [DateTimeOffset](./datetimeoffset/) | มีวันที่และเวลาตามเวลา UTC อ็อบเจ็กต์ของคลาสนี้ควรจัดสรรด้วยฟังก์ชัน [System::MakeObject()](./makeobject/) เท่านั้น ไม่ควรสร้างอินสแตนซ์บนสแต็กหรือใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบ ควรห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](./smartptr/) แล้วใช้ตัวชี้นี้ส่งให้ฟังก์ชันเป็นอาร์กิวเมนต์ |
| [DBNull](./dbnull/) | แสดงค่าที่ไม่มีอยู่ อ็อบเจ็กต์ของคลาสนี้ควรจัดสรรด้วยฟังก์ชัน [System::MakeObject()](./makeobject/) เท่านั้น ไม่ควรสร้างอินสแตนซ์บนสแต็กหรือใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบ ควรห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](./smartptr/) แล้วใช้ตัวชี้นี้ส่งให้ฟังก์ชันเป็นอาร์กิวเมนต์ |
| [Decimal](./decimal/) | แสดงจำนวนเลขฐานสิบ ประเภทนี้ควรจัดสรรบนสแต็กและส่งให้ฟังก์ชันโดยค่า หรือโดยอ้างอิง ไม่ควรใช้คลาส [System::SmartPtr](./smartptr/) เพื่อจัดการอ็อบเจ็กต์ประเภทนี้ |
| [DefaultBoxedValue](./defaultboxedvalue/) | การดำเนินการของคลาส [BoxedValue](./boxedvalue/) ทำให้สามารถประกาศการทำเฉพาะ BoxingValue ได้โดยไม่ต้องทำซ้ำโค้ดทั่วไป อ็อบเจ็กต์ของคลาสนี้ควรจัดสรรด้วยฟังก์ชัน [System::MakeObject()](./makeobject/) เท่านั้น ไม่ควรสร้างอินสแตนซ์บนสแต็กหรือใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบ ควรห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](./smartptr/) แล้วใช้ตัวชี้นี้ส่งให้ฟังก์ชันเป็นอาร์กิวเมนต์ |
| [Delegate< ReturnType(ArgumentTypes...)>](./delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/) | แสดงตัวชี้ไปยังฟังก์ชัน เมธอด หรืออ็อบเจ็กต์ฟังก์ชัน ประเภทนี้ควรจัดสรรบนสแต็กและส่งให้ฟังก์ชันโดยค่า หรือโดยอ้างอิง ไม่ควรใช้คลาส [System::SmartPtr](./smartptr/) เพื่อจัดการอ็อบเจ็กต์ประเภทนี้ |
| [Details_AggregateException](./details_aggregateexception/) | แสดงข้อยกเว้นที่มีข้อยกเว้นภายในหลายข้อ |
| [Details_ApplicationException](./details_applicationexception/) | คลาสฐานสำหรับคลาสที่แสดงข้อยกเว้นของแอปพลิเคชัน (ไม่ใช่ระบบ) ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส ApplicationException แทน ไม่ควรห่ออินสแตนซ์ของคลาส ApplicationException ด้วย [System::SmartPtr](./smartptr/) |
| [Details_ArgumentException](./details_argumentexception/) | ArgumentException จะถูกโยนเมื่ออาร์กิวเมนต์ที่ส่งให้เมธอดที่เรียกใช้มีค่าไม่ถูกต้อง ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส ArgumentException แทน ไม่ควรห่ออินสแตนซ์ของคลาส ArgumentException ด้วย [System::SmartPtr](./smartptr/) |
| [Details_ArgumentNullException](./details_argumentnullexception/) |  |
| [Details_ArgumentOutOfRangeException](./details_argumentoutofrangeexception/) | ArgumentOutOfRangeException จะถูกโยนเมื่อเมธอดที่เรียกใช้ได้รับอาร์กิวเมนต์ที่อยู่นอกช่วงค่าที่คาดหวังสำหรับอาร์กิวเมนต์นั้น ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส ArgumentOutOfRangeException แทน ไม่ควรห่ออินสแตนซ์ของคลาส ArgumentOutOfRangeException ด้วย [System::SmartPtr](./smartptr/) |
| [Details_ArithmeticException](./details_arithmeticexception/) | ArithmeticException จะถูกโยนเมื่อเกิดข้อผิดพลาดระหว่างการทำงานของการคำนวณ หรือการแปลงการคาสท์ ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส ArithmeticException แทน ไม่ควรห่ออินสแตนซ์ของคลาส ArithmeticException ด้วย [System::SmartPtr](./smartptr/) |
| [Details_BadImageFormatException](./details_badimageformatexception/) | ข้อยกเว้นที่โยนเมื่อไฟล์อิมเมจของไลบรารีลิงก์ไดนามิก (DLL) หรือโปรแกรมที่ทำงานได้ไม่ถูกต้อง ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส BadImageFormatException แทน ไม่ควรห่ออินสแตนซ์ของคลาส BadImageFormatException ด้วย [System::SmartPtr](./smartptr/) |
| [Details_DataMisalignedException](./details_datamisalignedexception/) |  |
| [Details_DivideByZeroException](./details_dividebyzeroexception/) | DivideByZeroException จะถูกโยนเมื่อพยายามหารด้วย 0 ในการดำเนินการคณิตศาสตร์ ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส DivideByZeroException แทน ไม่ควรห่ออินสแตนซ์ของคลาส DivideByZeroException ด้วย [System::SmartPtr](./smartptr/) |
| [Details_Exception](./details_exception/) | แสดงข้อยกเว้น ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส Exception แทน ไม่ควรห่ออินสแตนซ์ของคลาส Exception ด้วย [System::SmartPtr](./smartptr/) |
| [Details_ExceptionWithErrorCode](./details_exceptionwitherrorcode/) | คลาสเทมเพลตสำหรับข้อยกเว้นที่มีรหัสข้อผิดพลาด |
| [Details_ExceptionWithFilename](./details_exceptionwithfilename/) | คลาสเทมเพลตสำหรับข้อยกเว้นที่มีชื่อไฟล์ |
| [Details_ExecutionEngineException](./details_executionengineexception/) | ExecutionEngineException มีไว้เพื่อเหตุผลความเข้ากันได้เท่านั้น |
| [Details_FormatException](./details_formatexception/) | FormatException จะถูกโยนเมื่อรูปแบบของอาร์กิวเมนต์ของเมธอดไม่ถูกต้อง ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส FormatException แทน ไม่ควรห่ออินสแตนซ์ของคลาส FormatException ด้วย [System::SmartPtr](./smartptr/) |
| [Details_IndexOutOfRangeException](./details_indexoutofrangeexception/) | IndexOutOfRangeException จะถูกโยนเมื่อพยายามเข้าถึงสมาชิกของคอลเลกชันด้วยดัชนีที่อยู่นอกขอบเขต ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส IndexOutOfRangeException แทน ไม่ควรห่ออินสแตนซ์ของคลาส IndexOutOfRangeException ด้วย [System::SmartPtr](./smartptr/) |
| [Details_InvalidCastException](./details_invalidcastexception/) | InvalidCastException จะถูกโยนเมื่อมีการคาสท์ที่ไม่ถูกต้องหรือการแปลงแบบชัดเจนที่ไม่ถูกต้อง ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส InvalidCastException แทน ไม่ควรห่ออินสแตนซ์ของคลาส InvalidCastException ด้วย [System::SmartPtr](./smartptr/) |
| [Details_InvalidOperationException](./details_invalidoperationexception/) | ข้อยกเว้นที่โยนเมื่อเมธอดถูกเรียกบนอ็อบเจ็กต์ที่อยู่ในสถานะไม่สอดคล้องกับการเรียก ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส InvalidOperationException แทน ไม่ควรห่ออินสแตนซ์ของคลาส InvalidOperationException ด้วย [System::SmartPtr](./smartptr/) |
| [Details_InvalidProgramException](./details_invalidprogramexception/) | InvalidProgramException มีไว้เพื่อเหตุผลความเข้ากันได้เท่านั้น ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส InvalidProgramException แทน ไม่ควรห่ออินสแตนซ์ของคลาส InvalidProgramException ด้วย [System::SmartPtr](./smartptr/) |
| [Details_InvalidTimeZoneException](./details_invalidtimezoneexception/) | InvalidTimeZoneException จะถูกโยนเมื่อข้อมูลเขตเวลามีค่าไม่ถูกต้อง ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส InvalidTimeZoneException แทน ไม่ควรห่ออินสแตนซ์ของคลาส InvalidTimeZoneException ด้วย [System::SmartPtr](./smartptr/) |
| [Details_MemberAccessException](./details_memberaccessexception/) | MemberAccessException จะถูกโยนเมื่อพยายามเข้าถึงสมาชิกของคลาสที่ไม่มีอยู่ หรือเมื่อการเข้าถึงสมาชิกนั้นไม่ได้รับอนุญาต ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส MemberAccessException แทน ไม่ควรห่ออินสแตนซ์ของคลาส MemberAccessException ด้วย [System::SmartPtr](./smartptr/) |
| [Details_MethodAccessException](./details_methodaccessexception/) | MemberAccessException จะถูกโยนเมื่อพยายามเข้าถึงเมธอดที่ไม่มีอยู่ หรือเมื่อการเข้าถึงเมธอดนั้นไม่ได้รับอนุญาต ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส MethodAccessException แทน ไม่ควรห่ออินสแตนซ์ของคลาส MethodAccessException ด้วย [System::SmartPtr](./smartptr/) |
| [Details_NotImplementedException](./details_notimplementedexception/) | NotImplementedException จะถูกโยนเมื่อเมธอดที่ยังไม่ได้ implement ทำหน้าที่เป็นสแตก ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส NotImplementedException แทน ไม่ควรห่ออินสแตนซ์ของคลาส NotImplementedException ด้วย [System::SmartPtr](./smartptr/) |
| [Details_NotSupportedException](./details_notsupportedexception/) | NotSupportedException จะถูกโยนเมื่อเมธอดที่เรียกใช้ไม่รองรับ หรือเมื่อการดำเนินการบนสตรีมไม่รองรับ ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส NotSupportedException แทน ไม่ควรห่ออินสแตนซ์ของคลาส NotSupportedException ด้วย [System::SmartPtr](./smartptr/) |
| [Details_NullReferenceException](./details_nullreferenceexception/) | NullReferenceException จะถูกโยนเมื่อพยายามอ้างอิงออบเจ็กต์ที่เป็น null ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส NullReferenceException แทน ไม่ควรห่ออินสแตนซ์ของคลาส NullReferenceException ด้วย [System::SmartPtr](./smartptr/) |
| [Details_ObjectDisposedException](./details_objectdisposedexception/) | ObjectDisposedException จะถูกโยนเมื่อเมธอดถูกเรียกบนอ็อบเจ็กต์ที่ถูกทำลาย ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส ObjectDisposedException แทน ไม่ควรห่ออินสแตนซ์ของคลาส ObjectDisposedException ด้วย [System::SmartPtr](./smartptr/) |
| [Details_OperationCanceledException](./details_operationcanceledexception/) | OperationCanceledException จะถูกโยนในเธรดเมื่อมีการยกเลิกการดำเนินงานที่เธรดกำลังทำอยู่ ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส OperationCanceledException แทน ไม่ควรห่ออินสแตนซ์ของคลาส OperationCanceledException ด้วย [System::SmartPtr](./smartptr/) |
| [Details_OutOfMemoryException](./details_outofmemoryexception/) |  |
| [Details_OverflowException](./details_overflowexception/) | OverflowException จะถูกโยนเมื่อการดำเนินการทำให้เกิดการ overflow ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส OverflowException แทน ไม่ควรห่ออินสแตนซ์ของคลาส OverflowException ด้วย [System::SmartPtr](./smartptr/) |
| [Details_PlatformNotSupportedException](./details_platformnotsupportedexception/) | PlatformNotSupportedException ถูกขว้างเมื่อฟีเจอร์ไม่ทำงานบนแพลตฟอร์มเฉพาะ. ห้ามสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส PlatformNotSupportedException แทน. ห้ามห่ออินสแตนซ์ของคลาส PlatformNotSupportedException เข้าไปใน [System::SmartPtr](./smartptr/). |
| [Details_RankException](./details_rankexception/) | RankException ถูกขว้างเมื่ออาเรย์อาร์กิวเมนต์ที่มีจำนวนมิติแตกต่างจากที่คาดหวังถูกส่งไปยังเมธอด. ห้ามสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส RankException แทน. ห้ามห่ออินสแตนซ์ของคลาส RankException เข้าไปใน [System::SmartPtr](./smartptr/). |
| [Details_StackOverflowException](./details_stackoverflowexception/) | StackOverflowException ถูกขว้างเมื่อสแต็กการทำงานของเธรดเต็ม. ห้ามสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส StackOverflowException แทน. ห้ามห่ออินสแตนซ์ของคลาส StackOverflowException เข้าไปใน [System::SmartPtr](./smartptr/). |
| [Details_SystemException](./details_systemexception/) | เป็นคลาสฐานสำหรับคลาสที่แสดงข้อยกเว้นของระบบ (ไม่ใช่แอปพลิเคชัน). ห้ามสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส SystemException แทน. ห้ามห่ออินสแตนซ์ของคลาส SystemException เข้าไปใน [System::SmartPtr](./smartptr/). |
| [Details_TimeoutException](./details_timeoutexception/) | TimeoutException แสดงว่าระยะเวลาที่จัดสรรให้กับกระบวนการหรือการทำงานได้หมดอายุ. ห้ามสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส TimeoutException แทน. ห้ามห่ออินสแตนซ์ของคลาส TimeoutException เข้าไปใน [System::SmartPtr](./smartptr/). |
| [Details_TimeZoneNotFoundException](./details_timezonenotfoundexception/) | TimeZoneNotFoundException ถูกขว้างเมื่อไม่พบข้อมูลเขตเวลา. ห้ามสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส TimeZoneNotFoundException แทน. ห้ามห่ออินสแตนซ์ของคลาส TimeZoneNotFoundException เข้าไปใน [System::SmartPtr](./smartptr/). |
| [Details_TypeInitializationException](./details_typeinitializationexception/) |  |
| [Details_UnauthorizedAccessException](./details_unauthorizedaccessexception/) | UnauthorizedAccessException ถูกขว้างเมื่อระบบปฏิบัติการปฏิเสธการเข้าถึงเนื่องจากข้อผิดพลาด I/O หรือข้อผิดพลาดด้านความปลอดภัย. ห้ามสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส UnauthorizedAccessException แทน. ห้ามห่ออินสแตนซ์ของคลาส UnauthorizedAccessException เข้าไปใน [System::SmartPtr](./smartptr/). |
| [Details_UriFormatException](./details_uriformatexception/) | UriFormatException ถูกขว้างเมื่อรูปแบบของ URI ไม่ถูกต้อง. ห้ามสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส UriFormatException แทน. ห้ามห่ออินสแตนซ์ของคลาส UriFormatException เข้าไปใน [System::SmartPtr](./smartptr/). |
| [DynamicWeakPtr](./dynamicweakptr/) | คลาส smart pointer ที่ติดตามโหมดของพอยเตอร์ของเทมเพลตอาร์กิวเมนต์ของวัตถุที่เก็บและอัปเดตหลังจากการกำหนดค่าแต่ละครั้ง. ชนิดนี้เป็นพอยเตอร์เพื่อจัดการการลบวัตถุอื่น. ควรจัดสรรบนสแต็กและส่งต่อไปยังฟังก์ชันโดยการส่งค่า หรือโดยการอ้างอิงแบบคอนสท์. |
| [EnumValues](./enumvalues/) | ให้ข้อมูลเมตาเกี่ยวกับค่าคงที่ของ enum ของประเภท enum **E**. |
| [EnumValuesBase](./enumvaluesbase/) | เป็นคลาสฐานสำหรับคลาสที่แสดงข้อมูลเมตาของประเภท enum. |
| [EventArgs](./eventargs/) | คลาสฐานสำหรับคลาสที่แสดงบริบทที่ส่งให้ผู้สมัครรับเหตุการณ์เมื่อเหตุการณ์ถูกเรียก. ออบเจกต์ของคลาสนี้ควรถูกจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](./makeobject/) เท่านั้น. ห้ามสร้างอินสแตนซ์ของชนิดนี้บนสแต็กหรือด้วยตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสนี้ด้วยพอยเตอร์ [System::SmartPtr](./smartptr/) และใช้พอยเตอร์นี้เพื่อส่งต่อเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน. |
| [ExceptionWrapper](./exceptionwrapper/) | เท็มเพลตที่เป็น wrapper ของข้อยกเว้นที่สืบทอดจากคลาส Exception. |
| [FlagsAttribute](./flagsattribute/) | บ่งชี้ว่า enumeration สามารถปฏิบัติเป็นบิตฟิลด์; นั่นคือ ชุดของ. |
| [Func](./func/) | ฟังก์ชัน delegate. ชนิดนี้ควรจัดสรรบนสแต็กและส่งต่อไปยังฟังก์ชันโดยการส่งค่า หรือโดยการอ้างอิง. ห้ามใช้คลาส [System::SmartPtr](./smartptr/) เพื่อจัดการออบเจกต์ของชนิดนี้. |
| [GC](./gc/) | เป็นตัวแทนของ Garbage Collection จำลองที่ทำหน้าที่เหมือนสตับซึ่งโดยปฏิบัติแล้วไม่ได้ทำอะไร. นี้เป็นชนิด static ที่ไม่มีบริการอินสแตนซ์. คุณไม่ควรสร้างอินสแตนซ์ของมันโดยวิธีใด ๆ. |
| [Guid](./guid/) | เป็นตัวแทนของ Globally Unique IDentifier ชนิดนี้ควรจัดสรรบนสแต็กและส่งต่อไปยังฟังก์ชันโดยการส่งค่า หรือโดยการอ้างอิง. ห้ามใช้คลาส [System::SmartPtr](./smartptr/) เพื่อจัดการออบเจกต์ของชนิดนี้. |
| [IAsyncResult](./iasyncresult/) | เป็นตัวแทนของสถานะของการทำงานแบบอะซิงโครนัส. ออบเจกต์ของคลาสนี้ควรถูกจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](./makeobject/) เท่านั้น. ห้ามสร้างอินสแตนซ์ของชนิดนี้บนสแต็กหรือด้วยตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสนี้ด้วยพอยเตอร์ [System::SmartPtr](./smartptr/) และใช้พอยเตอร์นี้เพื่อส่งต่อเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน. |
| [ICloneable](./icloneable/) | กำหนดเมธอดที่เปิดใช้งานการโคลนนิงของอ็อบเจกต์ - การสร้างสำเนาของอ็อบเจกต์. ออบเจกต์ของคลาสนี้ควรถูกจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](./makeobject/) เท่านั้น. ห้ามสร้างอินสแตนซ์ของชนิดนี้บนสแต็กหรือด้วยตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสนี้ด้วยพอยเตอร์ [System::SmartPtr](./smartptr/) และใช้พอยเตอร์นี้เพื่อส่งต่อเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน. |
| [IComparable](./icomparable/) | กำหนดเมธอดที่เปรียบเทียบอ็อบเจกต์สองอัน. ออบเจกต์ของคลาสนี้ควรถูกจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](./makeobject/) เท่านั้น. ห้ามสร้างอินสแตนซ์ของชนิดนี้บนสแต็กหรือด้วยตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสนี้ด้วยพอยเตอร์ [System::SmartPtr](./smartptr/) และใช้พอยเตอร์นี้เพื่อส่งต่อเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน. |
| [IConvertible](./iconvertible/) | กำหนดเมธอดที่แปลงค่าของอ้างอิงหรือชนิดค่าที่ทำหน้าที่เป็นประเภท runtime ของภาษาแบบทั่วไปที่มีค่าเทียบเท่า. ออบเจกต์ของคลาสนี้ควรถูกจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](./makeobject/) เท่านั้น. ห้ามสร้างอินสแตนซ์ของชนิดนี้บนสแต็กหรือด้วยตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสนี้ด้วยพอยเตอร์ [System::SmartPtr](./smartptr/) และใช้พอยเตอร์นี้เพื่อส่งต่อเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน. |
| [ICustomFormatter](./icustomformatter/) | กำหนดเมธอดที่ทำการฟอร์แมตแบบกำหนดเองของสตริงที่เป็นตัวแทนค่าโดยออบเจกต์ที่ระบุ. ออบเจกต์ของคลาสนี้ควรถูกจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](./makeobject/) เท่านั้น. ห้ามสร้างอินสแตนซ์ของชนิดนี้บนสแต็กหรือด้วยตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสนี้ด้วยพอยเตอร์ [System::SmartPtr](./smartptr/) และใช้พอยเตอร์นี้เพื่อส่งต่อเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน. |
| [IDisposable](./idisposable/) | กำหนดเมธอดที่ปล่อยทรัพยากรที่ออบเจกต์ปัจจุบันเป็นเจ้าของ. ออบเจกต์ของคลาสนี้ควรถูกจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](./makeobject/) เท่านั้น. ห้ามสร้างอินสแตนซ์ของชนิดนี้บนสแต็กหรือด้วยตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสนี้ด้วยพอยเตอร์ [System::SmartPtr](./smartptr/) และใช้พอยเตอร์นี้เพื่อส่งต่อเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน. |
| [IEquatable](./iequatable/) | กำหนดเมธอดที่กำหนดความเท่าเทียมของอ็อบเจกต์สองอัน. ออบเจกต์ของคลาสนี้ควรถูกจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](./makeobject/) เท่านั้น. ห้ามสร้างอินสแตนซ์ของชนิดนี้บนสแต็กหรือด้วยตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสนี้ด้วยพอยเตอร์ [System::SmartPtr](./smartptr/) และใช้พอยเตอร์นี้เพื่อส่งต่อเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน. |
| [IFormatProvider](./iformatprovider/) | กำหนดเมธอดที่ให้ข้อมูลการฟอร์แมต. ออบเจกต์ของคลาสนี้ควรถูกจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](./makeobject/) เท่านั้น. ห้ามสร้างอินสแตนซ์ของชนิดนี้บนสแต็กหรือด้วยตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสนี้ด้วยพอยเตอร์ [System::SmartPtr](./smartptr/) และใช้พอยเตอร์นี้เพื่อส่งต่อเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน. |
| [IFormattable](./iformattable/) | กำหนดเมธอดที่ฟอร์แมตค่าของอ็อบเจกต์ปัจจุบันโดยใช้สตริงรูปแบบและผู้ให้บริการรูปแบบที่ระบุ. |
| [Index](./index/) | เป็นตัวแทนของดัชนีในคอลเลกชัน. ดัชนีสามารถนับจากจุดเริ่มต้นหรือจากจุดสิ้นสุด. ชนิดนี้ควรจัดสรรบนสแต็กและส่งต่อไปยังฟังก์ชันโดยการส่งค่า หรือโดยการอ้างอิง. ห้ามใช้คลาส [System::SmartPtr](./smartptr/) เพื่อจัดการออบเจกต์ของชนิดนี้. |
| [Int16](./int16/) | มีเมธอดสำหรับทำงานกับจำนวนเต็ม 16-bit. |
| [Int32](./int32/) | มีเมธอดสำหรับทำงานกับจำนวนเต็ม 32-bit. |
| [Int64](./int64/) | มีเมธอดสำหรับทำงานกับจำนวนเต็ม 64-bit. |
| [LockContext](./lockcontext/) | อ็อบเจกต์ Guard ที่ทำหน้าที่เป็นคำสั่ง lock() ของ C#. |
| [MarshalByRefObject](./marshalbyrefobject/) | ให้การเข้าถึงออบเจกต์ข้ามขอบเขตของโดเมนแอปพลิเคชันในแอปพลิเคชันที่เปิดใช้การรีโมต. ออบเจกต์ของคลาสนี้ควรถูกจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](./makeobject/) เท่านั้น. ห้ามสร้างอินสแตนซ์ของชนิดนี้บนสแต็กหรือด้วยตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสนี้ด้วยพอยเตอร์ [System::SmartPtr](./smartptr/) และใช้พอยเตอร์นี้เพื่อส่งต่อเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน. |
| [MulticastDelegate< ReturnType(ArgumentTypes...)>](./multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/) | เป็นตัวแทนของคอลเลกชันของ delegate. ชนิดนี้ควรจัดสรรบนสแต็กและส่งต่อไปยังฟังก์ชันโดยการส่งค่า หรือโดยการอ้างอิง. ห้ามใช้คลาส [System::SmartPtr](./smartptr/) เพื่อจัดการออบเจกต์ของชนิดนี้. |
| [Nullable](./nullable/) | การประกาศล่วงหน้า. |
| [NullableUtils](./nullableutils/) | เป็นตัวแทนของคลาส static C# [System.Nullable](./nullable/) (โดยไม่มีอาร์กิวเมนต์ประเภท). ไม่สามารถใช้ชื่อเดิมได้เนื่องจากไม่สามารถ overload เทมแพลตคลาสใน C++. รองรับประเภทค่าที่สามารถกำหนดเป็น null. คลาสนี้ไม่สามารถสืบทอดได้. |
| [Object](./object/) | คลาสฐานที่ทำให้สามารถใช้เมธอดที่มีอยู่สำหรับคลาส [System.Object](./object/) ใน C# ได้. ทุกคลาสที่ไม่ใช่แบบธรรมดาที่ใช้กับสภาพแวดล้อมที่แปลแล้วควรสืบทอดจากมัน. |
| [ObjectExt](./objectext/) | ให้เมธอด static ที่จำลองเมธอด C# [Object](./object/) ที่เรียกสำหรับประเภท C++ ที่ไม่ใช่ Object (เช่น สตริง, ตัวเลข ฯลฯ). นี้เป็นชนิด static ที่ไม่มีบริการอินสแตนซ์. คุณไม่ควรสร้างอินสแตนซ์ของมันโดยวิธีใด ๆ. |
| [ObjectType](./objecttype/) | ให้เมธอด static ที่ทำหน้าที่เป็น getter ของประเภทอ็อบเจกต์. นี้เป็นชนิด static ที่ไม่มีบริการอินสแตนซ์. คุณไม่ควรสร้างอินสแตนซ์ของมันโดยวิธีใด ๆ. |
| [OperatingSystem](./operatingsystem/) | เป็นตัวแทนของระบบปฏิบัติการเฉพาะและให้ข้อมูลเกี่ยวกับมัน. ออบเจกต์ของคลาสนี้ควรถูกจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](./makeobject/) เท่านั้น. ห้ามสร้างอินสแตนซ์ของชนิดนี้บนสแต็กหรือด้วยตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสนี้ด้วยพอยเตอร์ [System::SmartPtr](./smartptr/) และใช้พอยเตอร์นี้เพื่อส่งต่อเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน. |
| [Random](./random/) | เป็นตัวแทนของตัวสร้างเลขสุ่มเทียม. ออบเจกต์ของคลาสนี้ควรถูกจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](./makeobject/) เท่านั้น. ห้ามสร้างอินสแตนซ์ของชนิดนี้บนสแต็กหรือด้วยตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสนี้ด้วยพอยเตอร์ [System::SmartPtr](./smartptr/) และใช้พอยเตอร์นี้เพื่อส่งต่อเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน. |
| [Range](./range/) | เป็นตัวแทนของช่วงที่มีดัชนีเริ่มต้นและจบ. ชนิดนี้ควรจัดสรรบนสแต็กและส่งต่อไปยังฟังก์ชันโดยการส่งค่า หรือโดยการอ้างอิง. ห้ามใช้คลาส [System::SmartPtr](./smartptr/) เพื่อจัดการออบเจกต์ของชนิดนี้. |
| [ReadOnlySpan](./readonlyspan/) | การ forward เพื่อใช้ภายในคลาส [Span](./span/). |
| [ScopedCulture](./scopedculture/) | เป็นตัวแทนของวัฒนธรรม (culture) ที่ใช้ภายในขอบเขต. |
| [SmartPtr](./smartptr/) | คลาสตัวชี้เพื่อห่อหุ้มชนิดที่จัดสรรบน heap. ใช้เพื่อจัดการหน่วยความจำสำหรับคลาสที่สืบทอดจาก [Object](./object/). ตัวชี้ชนิดนี้ทำตามหลักการของ intrusive pointer. ตัวนับอ้างอิงถูกเก็บไว้ใน [Object](./object/) เองหรือในโครงสร้างตัวนับที่ผูกกับอินสแตนซ์ [Object](./object/) อย่างแน่นหนา. ไม่ว่าอย่างไร อินสแตนซ์ [SmartPtr](./smartptr/) ทั้งหมดจะเป็นกลุ่มครอบครองเดียวกันโดยไม่สนใจว่าจะสร้างอย่างไร ซึ่งแตกต่างจากพฤติกรรมของคลาส std::shared_ptr. การแปลง raw pointer ไปเป็น [SmartPtr](./smartptr/) จะปลอดภัยหากมีอินสแตนซ์ [SmartPtr](./smartptr/) อื่น ๆ ที่ถืออ้างอิงร่วมไปยังวัตถุเดียวกัน. อินสแตนซ์คลาส [SmartPtr](./smartptr/) สามารถอยู่ในสองสถานะ: shared pointer และ weak pointer. เพื่อให้วัตถุอยู่รอด ผู้ใช้ต้องมีจำนวนอ้างอิง shared ที่เป็นบวก. ทั้ง weak และ shared pointer สามารถใช้เพื่อเข้าถึงวัตถุที่ชี้ (เรียกเมธอด, อ่านหรือเขียนฟิลด์ ฯลฯ) แต่ weak pointer จะไม่เข้าร่วมการนับอ้างอิงของ shared pointer. [Object](./object/) จะถูกลบเมื่อ pointer [SmartPtr](./smartptr/) แบบ 'shared' ตัวสุดท้ายที่ชี้ไปถูกทำลาย. ดังนั้นให้มั่นใจว่าเหตุการณ์นี้ไม่เกิดขึ้นเมื่อไม่มี pointer [SmartPtr](./smartptr/) แบบ shared อื่นชี้ไปยังวัตถุ, เช่น ระหว่างการสร้างหรือทำลายวัตถุ. ใช้วัตถุ sentry System::Object::ThisProtector (ในโค้ด C++) หรือแอตทริบิวต์ CppCTORSelfReference หรือ CppSelfReference (ในโค้ด C# ที่แปล) เพื่อแก้ไขปัญหานี้. ในทำนองเดียวกัน, ให้แน่ใจว่าตัดการอ้างอิงแบบวนลูปด้วยการใช้คลาส pointer [System::WeakPtr](./weakptr/) หรือโหมด pointer [System::SmartPtrMode::Weak](./smartptrmode/) (ในโค้ด C++) หรือแอตทริบิวต์ CppWeakPtr (ในโค้ด C# ที่แปล). ถ้าวัตถุสองหรือมากกว่าระบุอ้างอิงถึงกันโดยใช้ pointer 'shared', พวกมันจะไม่ถูกลบ. ถ้าต้องการสลับประเภท pointer (weak หรือ shared) ในเวลารันไทม์, ใช้วิธี [System::SmartPtr<T>::set_Mode()](./smartptr/set_mode/) หรือคลาส [System::DynamicWeakPtr](./dynamicweakptr/). คลาส [SmartPtr](./smartptr/) ไม่มีเมธอด virtual ใด ๆ. ควรสืบทอดเท่านั้นหากคุณกำลังสร้างกลยุทธ์การจัดการหน่วยความจำของคุณเอง. ชนิดนี้เป็น pointer เพื่อจัดการการลบของวัตถุอื่น. ควรจัดสรรบน stack และส่งให้ฟังก์ชันโดยค่า หรือโดย const reference. |
| [SmartPtrInfo](./smartptrinfo/) | คลาสบริการเพื่อทดสอบและแก้ไขเนื้อหาของ [SmartPtr](./smartptr/) โดยไม่ต้องรู้ประเภทขั้นสุดท้าย. ใช้สำหรับการจัดเก็บขยะและการตรวจจับการอ้างอิงวนลูป, ฯลฯ คิดว่าเป็น 'pointer to pointer'. เราไม่สามารถใช้ basetype ของ [SmartPtr](./smartptr/) ได้เพราะมันไม่มี; ดังนั้นจึงใช้คลาส 'info' นี้. |
| [Span](./span/) | แสดงถึงบริเวณหน่วยความจำต่อเนื่องของชนิดใดก็ได้คล้ายกับ std::span ของ C++20. |
| [String](./string/) | คลาส [String](./string/) ที่ใช้ทั่วไลบรารี. เป็นตัวแทนของ C# [System.String](./string/) เมื่อแปลงโค้ด. เนื่องจากเหตุผลด้านประสิทธิภาพ, ไม่ถือเป็น subclass ของ [Object](./object/). ชนิดนี้ควรจัดสรรบน stack และส่งให้ฟังก์ชันโดยค่า หรือโดย reference. อย่าใช้คลาส [System::SmartPtr](./smartptr/) เพื่อจัดการออบเจ็กต์ของชนิดนี้. |
| [StringComparer](./stringcomparer/) | เปรียบเทียบสตริงโดยใช้โหมดการเปรียบเทียบต่าง ๆ. ออบเจ็กต์ของคลาสนี้ควรสร้างด้วยฟังก์ชัน [System::MakeObject()](./makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของชนิดนี้บน stack หรือโดยใช้ operator new, เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการล้มเหลวของ assertion. ควรหุ้มคลาสนี้ด้วย pointer [System::SmartPtr](./smartptr/) และใช้ pointer นี้ส่งเป็นอาร์กิวเมนต์ให้ฟังก์ชัน. |
| [StringHashCompiletime](./stringhashcompiletime/) | คลาสช่วยเหลือที่สร้างค่าฮัชจาก c-string. |
| [TimeSpan](./timespan/) | แสดงถึงช่วงเวลา. ชนิดนี้ควรจัดสรรบน stack และส่งให้ฟังก์ชันโดยค่า หรือโดย reference. อย่าใช้คลาส [System::SmartPtr](./smartptr/) เพื่อจัดการออบเจ็กต์ของชนิดนี้. |
| [TimeZone](./timezone/) | แสดงถึงโซนเวลา. ออบเจ็กต์ของคลาสนี้ควรสร้างด้วยฟังก์ชัน [System::MakeObject()](./makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของชนิดนี้บน stack หรือโดยใช้ operator new, เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการล้มเหลวของ assertion. ควรหุ้มคลาสนี้ด้วย pointer [System::SmartPtr](./smartptr/) และใช้ pointer นี้ส่งเป็นอาร์กิวเมนต์ให้ฟังก์ชัน. |
| [TimeZoneInfo](./timezoneinfo/) | แสดงถึงข้อมูลที่อธิบายโซนเวลาตรงนั้น. ออบเจ็กต์ของคลาสนี้ควรสร้างด้วยฟังก์ชัน [System::MakeObject()](./makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของชนิดนี้บน stack หรือโดยใช้ operator new, เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการล้มเหลวของ assertion. ควรหุ้มคลาสนี้ด้วย pointer [System::SmartPtr](./smartptr/) และใช้ pointer นี้ส่งเป็นอาร์กิวเมนต์ให้ฟังก์ชัน. |
| [Tuple](./tuple/) | คลาสที่แสดงถึงโครงสร้างข้อมูล tuple. จำนวนรายการสูงสุดคือ 8. |
| [TupleFactory](./tuplefactory/) | ให้เมธอด static สำหรับสร้างอ็อบเจ็กต์ tuple. |
| [TypeInfo](./typeinfo/) | แสดงถึงชนิดเฉพาะและให้ข้อมูลเกี่ยวกับมัน. |
| [Uri](./uri/) | ตัวระบุทรัพยากรสากล. ออบเจ็กต์ของคลาสนี้ควรสร้างด้วยฟังก์ชัน [System::MakeObject()](./makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของชนิดนี้บน stack หรือโดยใช้ operator new, เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการล้มเหลวของ assertion. ควรหุ้มคลาสนี้ด้วย pointer [System::SmartPtr](./smartptr/) และใช้ pointer นี้ส่งเป็นอาร์กิวเมนต์ให้ฟังก์ชัน. |
| [UriBuilder](./uribuilder/) | ให้เมธอดสำหรับสร้างและแก้ไข universal resource identifiers (URIs). ออบเจ็กต์ของคลาสนี้ควรสร้างด้วยฟังก์ชัน [System::MakeObject()](./makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของชนิดนี้บน stack หรือโดยใช้ operator new, เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการล้มเหลวของ assertion. ควรหุ้มคลาสนี้ด้วย pointer [System::SmartPtr](./smartptr/) และใช้ pointer นี้ส่งเป็นอาร์กิวเมนต์ให้ฟังก์ชัน. |
| [UriParser](./uriparser/) | ใช้สำหรับแยกสคริปต์ URI scheme ใหม่. ออบเจ็กต์ของคลาสนี้ควรสร้างด้วยฟังก์ชัน [System::MakeObject()](./makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของชนิดนี้บน stack หรือโดยใช้ operator new, เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการล้มเหลวของ assertion. ควรหุ้มคลาสนี้ด้วย pointer [System::SmartPtr](./smartptr/) และใช้ pointer นี้ส่งเป็นอาร์กิวเมนต์ให้ฟังก์ชัน. |
| [UriShim](./urishim/) | คลาสบริการ. |
| [ValueTuple](./valuetuple/) | คลาสที่แสดงถึงโครงสร้างข้อมูล [ValueTuple](./valuetuple/). |
| [ValueType](./valuetype/) | คลาสฐานสำหรับชนิดค่าที่สืบทอดจาก [Object](./object/) ถูกตัดทอนเพื่อประสิทธิภาพ. ชนิดนี้ควรจัดสรรบน stack และส่งให้ฟังก์ชันโดยค่า หรือโดย reference. อย่าใช้คลาส [System::SmartPtr](./smartptr/) เพื่อจัดการออบเจ็กต์ของชนิดนี้. |
| [Version](./version/) | แสดงถึงหมายเลขเวอร์ชัน. ชนิดนี้ควรจัดสรรบน stack และส่งให้ฟังก์ชันโดยค่า หรือโดย reference. อย่าใช้คลาส [System::SmartPtr](./smartptr/) เพื่อจัดการออบเจ็กต์ของชนิดนี้. |
| [Void](./void/) |  |
| [WeakPtr](./weakptr/) | ซับคลาสของ [System::SmartPtr](./smartptr/) ที่ตั้งค่าให้เป็นโหมด weak ตอนสร้าง. โปรดทราบว่าคลาสนี้ไม่รับประกันว่าอินสแตนซ์จะอยู่ในโหมด weak ตลอดเวลาเนื่องจาก [set_Mode()](./smartptr/set_mode/) ยังสามารถเข้าถึงได้. ชนิดนี้เป็น pointer เพื่อจัดการการลบของวัตถุอื่น. ควรจัดสรรบน stack และส่งให้ฟังก์ชันโดยค่า หรือโดย const reference. |
| [WeakReference< T >](./weakreference_tmpl_t__end_tmpl/) | แสดงถึง weak reference, ซึ่งอ้างอิงวัตถุพร้อมยังคงให้วัตถุนั้นถูกลบได้. |
| [WeakReference<>](./weakreference_tmpl_end_tmpl/) | แสดงถึง weak reference, ซึ่งอ้างอิงวัตถุพร้อมยังคงให้วัตถุนั้นถูกลบได้. |
## โครงสร้าง

| Struct | Description |
| --- | --- |
| [CastResult](./castresult/) | เทมเพลตเมจิกเพื่อสรุปผลการแคสท์. |
| [CollectionAssertHelper](./collectionasserthelper/) | API ผู้ช่วยสำหรับปฏิบัติการที่เกี่ยวกับคอลเลกชัน. |
| [Convert](./convert/) | โครงสร้างที่มีเมธอดทำการแปลงค่าชนิดหนึ่งเป็นค่าอีกชนิดหนึ่ง. ชนิดนี้ควรจัดสรรบน stack และส่งให้ฟังก์ชันโดยค่า หรือโดย reference. อย่าใช้คลาส [System::SmartPtr](./smartptr/) เพื่อจัดการออบเจ็กต์ของชนิดนี้. |
| [Double](./double/) | มีเมธอดสำหรับทำงานกับเลขทศนิยมความละเอียดคู่. |
| [Enum](./enum/) | ให้เมธอดที่ทำการปฏิบัติกับค่าชนิด enum. นี้เป็นชนิด static ไม่มีบริการอินสแตนซ์. คุณไม่ควรสร้างอินสแตนซ์ของมันโดยวิธีใด ๆ. |
| [EnumGetNameHelper](./enumgetnamehelper/) | คลาสผู้ช่วยที่ให้ฟังก์ชันการรับชื่อสตริงของค่าคงที่ enum. |
| [EnumParseHelper](./enumparsehelper/) | คลาสผู้ช่วยที่ให้ฟังก์ชันการแปลงสตริงของค่าคงที่ enum ไปเป็นค่า enum ที่เทียบเท่า. |
| [Environment](./environment/) | เวอร์ชันบริการของ [Environment](./environment/). นี้เป็นชนิด static ไม่มีบริการอินสแตนซ์. คุณไม่ควรสร้างอินสแตนซ์ของมันโดยวิธีใด ๆ. |
| [HolderInitializer](./holderinitializer/) | คลาสนี้ใช้เพื่อรับอ้างอิงคงที่ต่ออินสแตนซ์ของออบเจ็กต์ ไม่ว่าจะเป็น lvalue หรือ rvalue. เพื่อให้ได้อ้างอิงดังกล่าว, ใช้เมธอด 'HoldIfTemporary' ที่มี overload สามตัว. สองตัวรับ rvalue เป็นพารามิเตอร์และคืนอ้างอิงไปยังมัน. ตัวที่สามรับ lvalue, ทำสำเนา pointer, แล้วคืนอ้างอิงไปยังสำเนานั้น. นอกจากนี้คลาสยังมีเมธอด 'Hold' เพื่อถือค่าที่ส่งมาโดยไม่มีเงื่อนไข (ใช้สำหรับคัดลอกค่าตัวแปร local บน stack หรืออ้างอิงลูกของมัน). |
| [HolderInitializer< T, false >](./holderinitializer_tmpl_t__false__end_tmpl/) | การสเปเชียลไลซ์ของ [HolderInitializer](./holderinitializer/) สำหรับกรณีที่ T เป็น value type. บริบทการใช้งานอนุญาตให้คืนอ้างอิงไปยังออบเจ็กต์ชั่วคราว, เนื่องจากรับประกันว่าตัวอินสแตนซ์จะถูกคัดลอกโดยผู้เรียก. ดังนั้นการสเปเชียลไลซ์นี้ใช้เป็นสตูบและทำอะไรไม่ได้. |
| [IsBoxable](./isboxable/) | พรีดิกซ์เทมเพลตที่ตรวจสอบว่าการบ็อกซิงของชนิดที่ระบุรองรับหรือไม่. |
| [IsExceptionWrapper](./isexceptionwrapper/) | พรีดิกซ์เทมเพลตที่กำหนดว่าชนิดที่ระบุเป็นคลาส Exception หรือคลาสลูกของมันหรือไม่. |
| [IsNullable](./isnullable/) | พรีดิกซ์เทมเพลตที่กำหนดว่าเทมเพลตอาร์กิวเมนต์ T อยู่ใน [Nullable](./nullable/) หรือคลาสย่อยของมันหรือไม่. |
| [IsSmartPtr](./issmartptr/) | คลาส trait เพื่อตรวจสอบว่าชนิดเป็นสเปเชียลไลซ์ของคลาส [SmartPtr](./smartptr/) หรือไม่. |
| [IsStringByteSequence](./isstringbytesequence/) | เทมเพลตเมจิกเพื่อตรวจสอบว่าชนิดเป็นลำดับของอักขระสตริงหรือไม่. |
| [IsStringLiteral](./isstringliteral/) | เทมเพลตเมจิกเพื่อตรวจสอบว่าชนิดเป็นลิเทรัลสตริงหรือไม่. |
| [IsStringPointer](./isstringpointer/) | เทมเพลตเมจิกเพื่อตรวจสอบว่าชนิดเป็น pointer ไปยังสตริงอักขระหรือไม่. |
| [IsWeakPtr](./isweakptr/) | คลาส trait เพื่อตรวจสอบว่าคลาสเฉพาะเป็นสเปเชียลไลซ์ของ [System::WeakPtr](./weakptr/) หรือไม่. ไม่ตรวจสอบว่าตัวอินสแตนซ์อยู่ในโหมด weak หรือไม่. |
| [MakeConstRef](./makeconstref/) | Trait เพื่อทำให้ชนิด generic เป็น \"const reference\" หากเป็น [String](./string/) หรือชนิด SmartPtr<>. |
| [Math](./math/) | มีฟังก์ชันคณิตศาสตร์. นี้เป็นชนิด static ไม่มีบริการอินสแตนซ์. คุณไม่ควรสร้างอินสแตนซ์ของมันโดยวิธีใด ๆ. |
| [MathF](./mathf/) | มีฟังก์ชันคณิตศาสตร์สำหรับค่าทศนิยมความละเอียดเดี่ยว. นี้เป็นชนิด static ไม่มีบริการอินสแตนซ์. คุณไม่ควรสร้างอินสแตนซ์ของมันโดยวิธีใด ๆ. |
| [MethodArgumentTuple< R(*)(Args...)>](./methodargumenttuple_tmpl_r_lbrace__star_rbrace__lbrace_args_dots_rbrace__end_tmpl/) | นิยาม tuple เพื่อเก็บอาร์กิวเมนต์ของเมธอด. |
| [MethodArgumentTuple< R(C::*)(Args...) const >](./methodargumenttuple_tmpl_r_lbrace_c__star_rbrace__lbrace_args_dots_rbrace__const__end_tmpl/) | นิยาม tuple เพื่อเก็บอาร์กิวเมนต์ของเมธอด. |
| [MethodArgumentTuple< R(C::*)(Args...)>](./methodargumenttuple_tmpl_r_lbrace_c__star_rbrace__lbrace_args_dots_rbrace__end_tmpl/) | นิยาม tuple เพื่อเก็บอาร์กิวเมนต์ของเมธอด. |
| [MulticastDelegateTypeInfo](./multicastdelegatetypeinfo/) | แสดงถึง pointer ไปยังออบเจ็กต์ [TypeInfo](./typeinfo/) ที่มีข้อมูลเกี่ยวกับคลาส MulticastDelegate. |
| [RemoveShared](./removeshared/) | Trait structs เพื่อลบ SharedPtr/WeakPtr จากชนิดอาร์กิวเมนต์. |
| [SByte](./sbyte/) | มีเมธอดทำงานกับ integer 8-bit. |
| [ScopeGuard](./scopeguard/) | คลาสบริการที่ให้บริการการเรียกฟังก์ชันอ็อบเจ็กต์บางอย่างเมื่ออินสแตนซ์ของคลาสออกจากขอบเขต. |
| [Single](./single/) | มีเมธอดทำงานกับเลขทศนิยมความละเอียดเดี่ยว. |
| [TestCompare](./testcompare/) | โครงสร้างบริการที่ให้ส่วนต่อประสานเพื่อเปรียบเทียบคอลเลกชัน. |
| [TestTools](./testtools/) | ให้ชุดเมธอดที่มีประโยชน์เพื่อตรวจสอบคุณสมบัติพื้นฐานของชนิดและฟังก์ชันต่าง ๆ. |
| [TestToolsExt](./testtoolsext/) | ฟังก์ชันทั่วไปสำหรับใช้ในการทดสอบการแปล. |
| [TypeInfoPtr](./typeinfoptr/) | Wrapper สำหรับ pointer ไปยังอินสแตนซ์ของคลาส [TypeInfo](./typeinfo/). ชนิดนี้ควรจัดสรรบน stack และส่งให้ฟังก์ชันโดยค่า หรือโดย reference. อย่าใช้คลาส [System::SmartPtr](./smartptr/) เพื่อจัดการออบเจ็กต์ของชนิดนี้. |
| [UInt16](./uint16/) | มีเมธอดทำงานกับ unsigned integer 16-bit. |
| [UInt32](./uint32/) | มีเมธอดทำงานกับ unsigned integer 32-bit. |
| [UInt64](./uint64/) | มีเมธอดทำงานกับ unsigned integer 64-bit. |
| [ValueTupleTypeInfo](./valuetupletypeinfo/) | แสดงถึง pointer ไปยังออบเจ็กต์ [TypeInfo](./typeinfo/) ที่มีข้อมูลเกี่ยวกับคลาส [ValueTuple](./valuetuple/). |
| [WeakPtrFromTypeParameter](./weakptrfromtypeparameter/) | Trait struct เพื่อแปลงชนิดอาร์กิวเมนต์เป็น weak-pointer หากเป็น pointer type. |
## ฟังก์ชัน

| Function | Description |
| --- | --- |
| [ArrayPtr](./arrayptr/)\<T\> [MakeArray](./makearray/)(std::initializer_list\<T\>) | ฟังก์ชัน factory ที่สร้างออบเจ็กต์ [Array](./array/) ใหม่, เติมด้วยสมาชิกจากรายการ initializer ที่ระบุและคืน smart pointer ที่ชี้ไปยังออบเจ็กต์ [Array](./array/). |
| [ArrayPtr](./arrayptr/)\<T\> [MakeArray](./makearray/)(Args\&&...) | ฟังก์ชัน factory ที่สร้างออบเจ็กต์ [Array](./array/) ใหม่โดยส่งอาร์กิวเมนต์ที่ระบุไปยังคอนสตรัคเตอร์ของมัน. |
| std::enable_if\<std::is_integral\<Integral\>::value, [ArrayPtr](./arrayptr/)\<T\>\>::type [MakeArray](./makearray/)(Integral, Args\&&...) | ฟังก์ชันแฟกทอรีที่สร้างอ็อบเจ็กต์ [Array](./array/) ใหม่โดยส่งอาร์กิวเมนต์ที่ระบุให้กับคอนสตรัคเตอร์ของมัน. |
| **bool** [operator==](./operator_equal_equal/)([ArraySegment](./arraysegment/)\<T\>, [ArraySegment](./arraysegment/)\<T\>) |  |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | กำหนดว่าอ็อบเจ็กต์ [Nullable](./nullable/) ที่ระบุเป็นค่าที่เท่ากับ null หรือไม่. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | กำหนดว่าค่าที่ระบุเท่ากับค่าที่อ็อบเจ็กต์ [Nullable](./nullable/) แสดงโดยการใช้ [operator==()](./operator_equal_equal/) กับค่าทั้งสองนี้หรือไม่. |
| **bool** [operator==](./operator_equal_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const [SmartPtr](./smartptr/)\<Y\>\&) | เปรียบเทียบความเท่ากันของ smart pointer สองตัว. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, [SmartPtr](./smartptr/)\<X\> const\&) | ตรวจสอบว่า smart pointer เป็น null หรือไม่. |
| std::enable_if\<std::is_base_of\<[Object](./object/), Y\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const Y *) | เปรียบเทียบความเท่ากันของ smart pointer กับตัวชี้ (C) ธรรมดา. |
| std::enable_if\<std::is_base_of\<[Object](./object/), X\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const X *, const [SmartPtr](./smartptr/)\<Y\>\&) | เปรียบเทียบความเท่ากันของ smart pointer กับตัวชี้ (C) ธรรมดา. |
| std::enable_if<\!std::is_scalar\<T\>::value\&&\!std::is_pointer\<T\>::value\&&\!std::is_array\<T\>::value\&&detail::has_method_is_null\<T\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(T const\&, std::nullptr_t) | ตรวจสอบว่าอ็อบเจ็กต์ประเภทค่า (โครงสร้าง C# ที่แปลเป็นอื่น ๆ) เป็น null หรือไม่. |
| std::enable_if<\!std::is_scalar\<T\>::value\&&\!std::is_pointer\<T\>::value\&&\!std::is_array\<T\>::value\&&detail::has_method_is_null\<T\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(std::nullptr_t, T const\&) | ตรวจสอบว่าอ็อบเจ็กต์ประเภทค่า (โครงสร้าง C# ที่แปลเป็นอื่น ๆ) เป็น null หรือไม่. |
| **bool** [operator==](./operator_equal_equal/)(Chars\&, const [String](./string/)\&) | [String](./string/) การเปรียบเทียบ. |
| **bool** [operator==](./operator_equal_equal/)(T\&, const [String](./string/)\&) | [String](./string/) การเปรียบเทียบ. |
| **bool** [operator==](./operator_equal_equal/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&, const [String](./string/)\&) | [Object](./object/) และการเปรียบเทียบสตริง. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, const [String](./string/)\&) | ตรวจสอบว่าสตริงเป็น null หรือไม่. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| **bool** [operator==](./operator_equal_equal/)(const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&, const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&) | กำหนดว่า URI ที่อ็อบเจ็กต์ปัจจุบันและอ็อบเจ็กต์ที่ระบุแสดงนั้นเท่ากันหรือไม่. |
| **bool** [operator!=](./operator_not_equal/)([ArraySegment](./arraysegment/)\<T\>, [ArraySegment](./arraysegment/)\<T\>) |  |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | กำหนดว่าอ็อบเจ็กต์ [Nullable](./nullable/) ที่ระบุเป็นค่าที่ไม่เท่ากับ null หรือไม่. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | กำหนดว่าค่าที่ระบุไม่เท่ากับค่าที่อ็อบเจ็กต์ [Nullable](./nullable/) แสดงโดยการใช้ [operator!=()](./operator_not_equal/) กับค่าทั้งสองนี้หรือไม่. |
| **bool** [operator!=](./operator_not_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const [SmartPtr](./smartptr/)\<Y\>\&) | เปรียบเทียบความไม่เท่ากันของ smart pointer สองตัว. |
| **bool** [operator!=](./operator_not_equal/)([SmartPtr](./smartptr/)\<X\> const\&, std::nullptr_t) | ตรวจสอบว่า smart pointer ไม่เป็น null. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, [SmartPtr](./smartptr/)\<X\> const\&) | ตรวจสอบว่า smart pointer ไม่เป็น null. |
| std::enable_if\<std::is_base_of\<[Object](./object/), Y\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const [SmartPtr](./smartptr/)\<X\>\&, const Y *) | เปรียบเทียบความไม่เท่ากันของ smart pointer กับตัวชี้ (C) ธรรมดา. |
| std::enable_if\<std::is_base_of\<[Object](./object/), X\>::value\&&detail::has_no_operator_equal\<X, Y\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const X *, const [SmartPtr](./smartptr/)\<Y\>\&) | เปรียบเทียบความเท่ากันของ smart pointer กับตัวชี้ (C) ธรรมดา. |
| **bool** [operator!=](./operator_not_equal/)(Chars\&, const [String](./string/)\&) | [String](./string/) การเปรียบเทียบ. |
| **bool** [operator!=](./operator_not_equal/)(T\&, const [String](./string/)\&) | [String](./string/) การเปรียบเทียบ. |
| **bool** [operator!=](./operator_not_equal/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&, const [String](./string/)\&) | [Object](./object/) และการเปรียบเทียบสตริง. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, const [String](./string/)\&) | ตรวจสอบว่าสตริงเป็น null หรือไม่. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| **bool** [operator!=](./operator_not_equal/)(const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&, const [SharedPtr](./sharedptr/)\<[Uri](./uri/)\>\&) | กำหนดว่า URI ที่อ็อบเจ็กต์ปัจจุบันและอ็อบเจ็กต์ที่ระบุแสดงนั้นไม่เท่ากันหรือไม่. |
| static **bool** [IsEnumMetaInfoDefined](./isenummetainfodefined/)(T) |  |
| static **bool** [IsEnumMetaInfoDefined](./isenummetainfodefined/)(T) |  |
| static [System::String](./string/) [EnumGetName](./enumgetname/)(T) |  |
| static [System::String](./string/) [EnumGetName](./enumgetname/)(T) |  |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator<](./operator_less/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | คืนค่า false เสมอ. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | กำหนดว่าค่าที่ระบุมีค่าน้อยกว่าค่าที่อ็อบเจ็กต์ [Nullable](./nullable/) แสดงโดยการใช้ [operator<()](./operator_less/) กับค่าทั้งสองนี้หรือไม่. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | คืนค่า false เสมอ. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | กำหนดว่าค่าที่ระบุมีค่าน้อยกว่าหรือเท่ากับค่าที่อ็อบเจ็กต์ [Nullable](./nullable/) แสดงโดยการใช้ [operator<=()](./operator_less_equal/) กับค่าทั้งสองนี้หรือไม่. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator>](./operator_greater/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | คืนค่า false เสมอ. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | กำหนดว่าค่าที่ระบุมีค่ามากกว่าค่าที่อ็อบเจ็กต์ [Nullable](./nullable/) แสดงโดยการใช้ [operator>()](./operator_greater/) กับค่าทั้งสองนี้หรือไม่. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, [DateTime](./datetime/)) |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, const [DateTimeOffset](./datetimeoffset/)\&) |  |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, const [Nullable](./nullable/)\<T\>\&) | คืนค่า false เสมอ. |
| std::enable_if<\![IsNullable](./isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | กำหนดว่าค่าที่ระบุมีค่ามากกว่าหรือเท่ากับค่าที่อ็อบเจ็กต์ [Nullable](./nullable/) แสดงโดยการใช้ [operator>=()](./operator_greater_equal/) กับค่าทั้งสองนี้หรือไม่. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t, [TimeSpan](./timespan/)) |  |
| void [PrintTo](./printto/)([DateTime](./datetime/), std::ostream *) | พิมพ์ค่าไปยัง ostream ส่วนใหญ่ใช้สำหรับการดีบั๊ก. |
| void [PrintTo](./printto/)([DateTimeOffset](./datetimeoffset/), std::ostream *) | พิมพ์ค่าไปยัง ostream ส่วนใหญ่ใช้สำหรับการดีบั๊ก. |
| void [PrintTo](./printto/)(const [Decimal](./decimal/)\&, ::std::ostream *) | เขียนค่าที่อ็อบเจ็กต์ที่ระบุแสดงไปยังสตรีมผลลัพธ์ที่ระบุ. |
| void [PrintTo](./printto/)(const [Details_Exception](./details_exception/)\&, std::ostream *) | พิมพ์ค่าไปยัง ostream ส่วนใหญ่ใช้สำหรับการดีบั๊ก. |
| void [PrintTo](./printto/)(const [ExceptionWrapper](./exceptionwrapper/)\<T\>\&, std::ostream *) | พิมพ์ค่าไปยัง ostream ส่วนใหญ่ใช้สำหรับการดีบั๊ก. |
| void [PrintTo](./printto/)(const [Guid](./guid/)\&, std::ostream *) | พิมพ์ค่าไปยัง ostream ส่วนใหญ่ใช้สำหรับการดีบั๊ก. |
| void [PrintTo](./printto/)(const [Nullable](./nullable/)\<T\>\&, std::ostream *) | พิมพ์ค่าไปยัง ostream ส่วนใหญ่ใช้สำหรับการดีบั๊ก. |
| void [PrintTo](./printto/)(const [System::Object](./object/)\&, std::ostream *) | พิมพ์ค่าไปยัง ostream ส่วนใหญ่ใช้สำหรับการดีบั๊ก. |
| std::enable_if_t\<detail::has_print_to_function\<T\>::value, void\> [PrintTo](./printto/)(const [SmartPtr](./smartptr/)\<T\>\&, std::ostream *) | พิมพ์ค่าไปยัง ostream ส่วนใหญ่ใช้สำหรับการดีบั๊ก. |
| std::enable_if_t<\!detail::has_print_to_function\<T\>::value, void\> [PrintTo](./printto/)(const [SmartPtr](./smartptr/)\<T\>\&, std::ostream *) | พิมพ์ค่าไปยัง ostream ส่วนใหญ่ใช้สำหรับการดีบั๊ก. |
| void [PrintTo](./printto/)(const [System::String](./string/)\&, std::ostream *) | พิมพ์สตริงไปยัง ostream ส่วนใหญ่ใช้สำหรับการดีบั๊ก. |
| void [PrintTo](./printto/)([TimeSpan](./timespan/), std::ostream *) | พิมพ์ค่าไปยัง ostream ส่วนใหญ่ใช้สำหรับการดีบั๊ก. |
| void [PrintTo](./printto/)(const [WeakPtr](./weakptr/)\<T\>\&, std::ostream *) | พิมพ์ค่าไปยัง ostream ส่วนใหญ่ใช้สำหรับการดีบั๊ก. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, [DateTime](./datetime/)) | แทรกข้อมูลลงในสตรีมโดยใช้การเข้ารหัส UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, [DateTime](./datetime/)) | แทรกข้อมูลลงในสตรีม. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, [DateTimeOffset](./datetimeoffset/)) | แทรกข้อมูลลงในสตรีมโดยใช้การเข้ารหัส UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, [DateTimeOffset](./datetimeoffset/)) | แทรกข้อมูลลงในสตรีม. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Decimal](./decimal/)\&) | แทรกข้อมูลลงในสตรีมโดยใช้การเข้ารหัส UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Decimal](./decimal/)\&) | แทรกข้อมูลลงในสตรีม. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Exception](./exception/)\&) | แทรกข้อมูลลงในสตรีมโดยใช้การเข้ารหัส UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Exception](./exception/)\&) | แทรกข้อมูลลงในสตรีม. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Guid](./guid/)\&) | แทรกข้อมูลลงในสตรีมโดยใช้การเข้ารหัส UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Guid](./guid/)\&) | แทรกข้อมูลลงในสตรีม. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Nullable](./nullable/)\<T\>\&) | แทรกข้อมูลลงในสตรีมโดยใช้การเข้ารหัส UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Nullable](./nullable/)\<T\>\&) | แทรกข้อมูลลงในสตรีม. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [System::Object](./object/)\&) | แทรกข้อมูลลงในสตรีมโดยใช้การเข้ารหัส UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [System::Object](./object/)\&) | แทรกข้อมูลลงในสตรีม. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [OperatingSystem](./operatingsystem/)\&) | แทรกข้อมูลลงในสตรีมโดยใช้การเข้ารหัส UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [OperatingSystem](./operatingsystem/)\&) | แทรกข้อมูลลงในสตรีม. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [SharedPtr](./sharedptr/)\<T\>\&) | แทรกข้อมูลลงในสตรีมโดยใช้การเข้ารหัส UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [SharedPtr](./sharedptr/)\<T\>\&) | แทรกข้อมูลลงในสตรีม. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [String](./string/)\&) | ส่งออกสตริงไปยังสตรีมผลลัพธ์โดยใช้การเข้ารหัส UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [String](./string/)\&) | ส่งออกสตริงไปยังสตรีมผลลัพธ์. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, [TimeSpan](./timespan/)) | แทรกข้อมูลลงในสตรีมโดยใช้การเข้ารหัส UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, [TimeSpan](./timespan/)) | แทรกข้อมูลลงในสตรีม. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [TypeInfo](./typeinfo/)\&) | แทรกข้อมูลลงในสตรีมโดยใช้การเข้ารหัส UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [TypeInfo](./typeinfo/)\&) | แทรกข้อมูลลงในสตรีม. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [Version](./version/)\&) | แทรกข้อมูลลงในสตรีมโดยใช้การเข้ารหัส UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [Version](./version/)\&) | แทรกข้อมูลลงในสตรีม. |
| std::ostream\& [operator<<](./operator_less_less/)(std::ostream\&, const [WeakPtr](./weakptr/)\<T\>\&) | แทรกข้อมูลลงในสตรีมโดยใช้การเข้ารหัส UTF-8. |
| std::wostream\& [operator<<](./operator_less_less/)(std::wostream\&, const [WeakPtr](./weakptr/)\<T\>\&) | แทรกข้อมูลลงในสตรีม. |
| auto [operator-](./operator_minus/)([DayOfWeek](./dayofweek/), [DayOfWeek](./dayofweek/)) | คำนวณจำนวนวันระหว่างวันของสัปดาห์สองวัน. |
| [Decimal](./decimal/) [operator-](./operator_minus/)(const T\&, const [Decimal](./decimal/)\&) | คืนค่าอินสแตนซ์ใหม่ของคลาส [Decimal](./decimal/) ที่แทนค่าผลลัพธ์ของการลบค่าที่อ็อบเจ็กต์ [Decimal](./decimal/) แสดงจากค่าที่ระบุ. |
| MulticastDelegate\<T\> [operator-](./operator_minus/)(MulticastDelegate\<T\>, MulticastDelegate\<T\>) | ตัดการเชื่อมต่อคอลแบ็กทั้งหมดในม_delegate ด้านขวาจากส่วนท้ายของรายการคอลแบ็กของม_delegate ด้านซ้าย. |

| auto [operator-](./operator_minus/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | ลบค่าที่ไม่เป็น null และค่าที่เป็น null. |
| [Decimal](./decimal/) [operator+](./operator_plus/)(const T\&, const [Decimal](./decimal/)\&) | คืนอินสแตนซ์ใหม่ของคลาส [Decimal](./decimal/) ที่แทนค่าซึ่งเป็นผลรวมของค่าที่ระบุและค่าที่แทนโดยอ็อบเจ็กต์ [Decimal](./decimal/) ที่ระบุ. |
| MulticastDelegate\<T\> [operator+](./operator_plus/)(MulticastDelegate\<T\>, MulticastDelegate\<T\>) | เชื่อมต่อคอลแบ็คทั้งหมดจาก delegate ด้านขวาไปยังส่วนท้ายของรายการคอลแบ็คของ delegate ด้านซ้าย. |
| auto [operator+](./operator_plus/)(const T1\&, const [Nullable](./nullable/)\<T2\>\&) | บวกค่าที่ไม่เป็น null และค่าที่เป็น null. |
| std::enable_if\<[IsStringLiteral](./isstringliteral/)\<T, char_t\>::value, [String](./string/)\>::type [operator+](./operator_plus/)(T\&, const [String](./string/)\&) | [String](./string/) การต่อสตริง. |
| std::enable_if\<[IsStringPointer](./isstringpointer/)\<T, char_t\>::value, [String](./string/)\>::type [operator+](./operator_plus/)(T\&, const [String](./string/)\&) | [String](./string/) การต่อสตริง. |
| [String](./string/) [operator+](./operator_plus/)(const char_t, const [String](./string/)\&) | [String](./string/) การต่อสตริง. |
| [Decimal](./decimal/) [operator*](./operator_star/)(const T\&, const [Decimal](./decimal/)\&) | คืนอินสแตนซ์ใหม่ของคลาส [Decimal](./decimal/) ที่แทนค่าซึ่งเป็นผลคูณของค่าที่ระบุและค่าที่แทนโดยอ็อบเจ็กต์ [Decimal](./decimal/) ที่ระบุ. |
| [Decimal](./decimal/) [operator/](./operator_div/)(const T\&, const [Decimal](./decimal/)\&) | คืนอินสแตนซ์ใหม่ของคลาส [Decimal](./decimal/) ที่แทนค่าซึ่งเป็นผลหารของค่าที่ระบุและค่าที่แทนโดยอ็อบเจ็กต์ [Decimal](./decimal/) ที่ระบุ. |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, constT\&\>::type [Default](./default/)() | คืนอ้างอิงไปยังอินสแตนซ์ที่สร้างขึ้นโดยค่าเริ่มต้นเพียงหนึ่งอันของประเภท exception. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, constT\&\>::type [Default](./default/)() | คืนอ้างอิงไปยังอินสแตนซ์ที่สร้างขึ้นโดยค่าเริ่มต้นเพียงหนึ่งอันของประเภทที่ไม่ใช่ exception. |
| T\& [Discard](./discard/)(T\&&) | คืนอินสแตนซ์ชั่วคราวที่สร้างโดยค่าเริ่มต้นของประเภทที่ระบุ ซึ่งสามารถใช้แทนการละทิ้งอาร์กิวเมนต์ '_' ได้. |
| Details::ObjectBuilder\<T, [SharedPtr](./sharedptr/)\<T\>\> [BuildObject](./buildobject/)(Args\&&...) | สร้างอ็อบเจ็กต์ที่มีการเป็นเจ้าของร่วม. |
| Details::ObjectBuilder\<T, [SharedPtr](./sharedptr/)\<T\>\> [InitObject](./initobject/)(const [SharedPtr](./sharedptr/)\<T\>\&) | เริ่มต้นการสร้างอ็อบเจ็กต์ที่มีการเป็นเจ้าของร่วม. |
| Details::ObjectBuilder\<Details::ArrayStorage\<T\>\> [BuildArray](./buildarray/)() | สร้างอาร์เรย์. |
| Details::ObjectBuilder\<T\> [Build](./build/)(Args\&&...) | สร้างอ็อบเจ็กต์ที่มีการเป็นเจ้าของโดยตรง. |
| **bool** [Is](./is/)(const ExpressionT\&, ResultT\&) | ทำการแปลรูปแบบการประกาศ 'is'. |
| std::enable_if_t<\!std::is_base_of\<Details::Pattern, ConstantT\>::value, **bool**\> [Is](./is/)(const ExpressionT\&, const ConstantT\&) | ทำการแปลรูปแบบคอนสแตนท์ 'is'. |
| std::enable_if_t\<std::is_base_of\<Details::Pattern, A\>::value, **bool**\> [Is](./is/)(const E\&, const A\&) | ฟังก์ชันการจับคู่ระดับบนสุด. ใช้รูปแบบกับค่า. |
| static **bool** [IsNull](./isnull/)(const T\&) | ทำการแปลรูปแบบ 'is null'. |
| **bool** [Less](./less/)(const ExpressionT\&, const ConstantT\&) | ทำการแปลรูปแบบสัมพันธ์ '<'. |
| **bool** [Greater](./greater/)(const ExpressionT\&, const ConstantT\&) | ทำการแปลรูปแบบสัมพันธ์ '>'. |
| **bool** [LEqual](./lequal/)(const ExpressionT\&, const ConstantT\&) | ทำการแปลรูปแบบสัมพันธ์ '<='. |
| **bool** [GEqual](./gequal/)(const ExpressionT\&, const ConstantT\&) | ทำการแปลรูปแบบสัมพันธ์ '>='. |
| **bool** [Set](./set/)(ExpressionT\&, const ExpressionT\&) | ทำการแปลรูปแบบ 'var'. |
| **bool** [IsTuple](./istuple/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&, **int32_t**) | ตรวจสอบว่าอ็อบเจ็กต์เป็น tuple (implements ITuple interface). ใช้ในการดำเนินรูปแบบตำแหน่ง. |
| auto [Get](./get/)(const [SharedPtr](./sharedptr/)\<[Object](./object/)\>\&) | ฟังก์ชันเพื่อดึงสมาชิกที่ N ของ tuple ที่กำหนด. การอิมพลีเมนต์สำหรับอ็อบเจ็กต์ฐาน. |
| auto [Get](./get/)(const T\&) | ฟังก์ชันเพื่อดึงสมาชิกที่ N ของ tuple ที่กำหนด. การอิมพลีเมนต์สำหรับอ็อบเจ็กต์ที่มีเมธอด Deconstruct. |
| auto [Get](./get/)(const [SharedPtr](./sharedptr/)\<T\>\&) | ฟังก์ชันเพื่อดึงสมาชิกที่ N ของ tuple ที่กำหนด. การอิมพลีเมนต์สำหรับ shared pointer. |
| auto\& [Get](./get/)(T\&, const [Index](./index/)\&) | การทำงานสำหรับนิพจน์ collection[index]. |
| auto [Get](./get/)(T\&, const [Range](./range/)\&) | คืนส่วนหนึ่งของคอลเลกชันที่กำหนดโดยช่วงที่ให้มา. |
| auto [Get](./get/)(const [ValueTuple](./valuetuple/)\<Args...\>\&) | ดึงสมาชิกที่ N ของ value tuple. |
| [SharedPtr](./sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<T\>\> [MakeYieldEnumerable](./makeyieldenumerable/)(const Details::YieldFunction\<T\>\&) | สร้าง IEnumerable จากฟังก์ชัน yield. |
| [SharedPtr](./sharedptr/)\<[Collections::Generic::IEnumerator](../system.collections.generic/ienumerator/)\<T\>\> [MakeYieldEnumerator](./makeyieldenumerator/)(const Details::YieldFunction\<T\>\&) | สร้าง IEnumerator จากฟังก์ชัน yield. |
| std::enable_if_t\<Details::is_lambda_void_void\<T\>::value\> [DoTryFinally](./dotryfinally/)(T\&&, F\&&) | ฟังก์ชันเดียวที่จำลองพฤติกรรมของคำสั่ง try[-catch]-finally ของ C#. เมื่อแปลคำสั่ง try[-catch]-finally ของ C# ด้วยตัวเลือก finally_statement_as_lambda ตั้งค่าเป็น true คำสั่งจะถูกแปลเป็นการเรียกเมธอดนี้. |
| std::enable_if_t\<Details::is_lambda_void_boolref\<T\>::value, **bool**\> [DoTryFinally](./dotryfinally/)(T\&&, F\&&) | ฟังก์ชันเดียวที่จำลองพฤติกรรมของคำสั่ง try[-catch]-finally ของ C#. เมื่อแปลคำสั่ง try[-catch]-finally ของ C# ด้วยตัวเลือก finally_statement_as_lambda ตั้งค่าเป็น true คำสั่งจะถูกแปลเป็นการเรียกเมธอดนี้. เวอร์ชันโอเวอร์โหลดนี้จัดการกรณีที่ค่าที่คืนจากฟังก์ชันอ็อบเจ็กต์ที่ทำหน้าที่ส่วน try[-catch] ของคำสั่ง try[-catch]-finally มีประเภทเป็น bool. |
| std::enable_if_t\<Details::is_lambda_nonovoid_boolref\<T\>::value, std::optional\<Details::ResultOf\<T, **bool**\&\>\>\> [DoTryFinally](./dotryfinally/)(T\&&, F\&&) | ฟังก์ชันเดียวที่จำลองพฤติกรรมของคำสั่ง try[-catch]-finally ของ C#. เมื่อแปลคำสั่ง try[-catch]-finally ของ C# ด้วยตัวเลือก finally_statement_as_lambda ตั้งค่าเป็น true คำสั่งจะถูกแปลเป็นการเรียกเมธอดนี้. เวอร์ชันโอเวอร์โหลดนี้จัดการกรณีที่ค่าที่คืนจากฟังก์ชันอ็อบเจ็กต์ที่ทำหน้าที่ส่วน try[-catch] ของคำสั่ง try[-catch]-finally มีประเภทเป็น bool&. |
| [DynamicWeakPtr](./dynamicweakptr/)\<T, trunkMode, weakLeafs...\>::Reference [Ref](./ref/)([DynamicWeakPtr](./dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\&) | สร้างการอ้างอิงไปยังอ็อบเจ็กต์ [DynamicWeakPtr](./dynamicweakptr/). ใช้โดย translator เมื่อส่งอาร์กิวเมนต์ฟังก์ชันโดยการอ้างอิง. |
| T\& [Ref](./ref/)(T\&) | ฟังก์ชันช่วยเพื่อรับอ้างอิงไปยังอ็อบเจ็กต์. ใช้เพื่อรับประกันว่า [System::DynamicWeakPtr](./dynamicweakptr/) จะอัพเดทอ็อบเจ็กต์ที่อ้างอิงหลังจากการกำหนดค่า. |
| std::enable_if_t<\!Details::IsIterable\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable, T\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | ฟังก์ชันพร็อพเพอร์ตี้นี้ห่อหุ้มอ็อบเจ็กต์ enumerable (หรือ iterable) เพื่อให้สามารถใช้กับลูป for-range ได้ เวอร์ชันโอเวอร์โหลดนี้สำหรับ Enumerable ที่ไม่มีเมธอด begin(), end() พร้อมอาร์กิวเมนต์ประเภทเป้าหมายสำหรับ (auto& value : IterateOver<SomeType>(enumerable)) |
| std::enable_if_t<\!Details::IsIterable\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | ฟังก์ชันพร็อพเพอร์ตี้นี้ห่อหุ้มอ็อบเจ็กต์ enumerable (หรือ iterable) เพื่อให้สามารถใช้กับลูป for-range ได้ เวอร์ชันโอเวอร์โหลดนี้สำหรับ Enumerable ที่ไม่มีเมธอด begin(), end() พร้อมอาร์กิวเมนต์ประเภทเป้าหมายค่าเริ่มต้นสำหรับ (auto& value : IterateOver(enumerable)) ซึ่งคล้ายกับโค้ด C# ต่อไปนี้ foreach (var value in enumerable) |
| std::enable_if_t\<Details::IsIterable\<Enumerable\>::value, [System::SmartPtr](./smartptr/)\<Enumerable\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | ฟังก์ชันพร็อพเพอร์ตี้นี้ห่อหุ้มอ็อบเจ็กต์ enumerable (หรือ iterable) เพื่อให้สามารถใช้กับลูป for-range ได้ เวอร์ชันโอเวอร์โหลดนี้สำหรับ Enumerable ที่มีเมธอด begin(), end() พร้อมอาร์กิวเมนต์ประเภทเป้าหมายค่าเริ่มต้นสำหรับ (auto& value : IterateOver(enumerable)) |
| std::enable_if_t\<Details::IsIterable\<Enumerable\>::value\&&std::is_same\<typename Details::ReturnTypeTrait\<T\>::ReturnType, Details::IterableValueType\<Enumerable\>\>::value, [System::SmartPtr](./smartptr/)\<Enumerable\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | ฟังก์ชันพร็อพเพอร์ตี้นี้ห่อหุ้มอ็อบเจ็กต์ enumerable (หรือ iterable) เพื่อให้สามารถใช้กับลูป for-range ได้ เวอร์ชันโอเวอร์โหลดนี้สำหรับ Enumerable ที่มีเมธอด begin(), end() พร้อมประเภทเป้าหมายเดียวกับ value_type ด้านต้นของ iterator. |
| std::enable_if_t\<Details::IsIterable\<Enumerable\>::value\&&\!std::is_same\<typename Details::ReturnTypeTrait\<T\>::ReturnType, Details::IterableValueType\<Enumerable\>\>::value, Details::CppIteratorAdapter\<Enumerable, T\>\> [IterateOver](./iterateover/)([System::SmartPtr](./smartptr/)\<Enumerable\>) | ฟังก์ชันพร็อพเพอร์ตี้นี้ห่อหุ้มอ็อบเจ็กต์ enumerable (หรือ iterable) เพื่อให้สามารถใช้กับลูป for-range ได้ เวอร์ชันโอเวอร์โหลดนี้สำหรับ Enumerable ที่มีเมธอด begin(), end() พร้อมประเภทเป้าหมายที่ต่างจาก value_type ด้านต้นของ iterator. |
| std::enable_if_t<\![IsSmartPtr](./issmartptr/)\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable, Details::ValueTypeOfEnumerable\<Enumerable\>, Enumerable *\>\> [IterateOver](./iterateover/)(const Enumerable *) | ฟังก์ชันพร็อพเพอร์ตี้นี้ห่อหุ้มอ็อบเจ็กต์ enumerable (หรือ iterable) เพื่อให้สามารถใช้กับลูป for-range ได้ เวอร์ชันโอเวอร์โหลดนี้สำหรับ Enumerable ที่เป็น this ด้วยประเภทเป้าหมายค่าเริ่มต้น. |
| std::enable_if_t<\![IsSmartPtr](./issmartptr/)\<Enumerable\>::value, Details::EnumeratorAdapter\<Enumerable, T, Enumerable *\>\> [IterateOver](./iterateover/)(const Enumerable *) | ฟังก์ชันพร็อพเพอร์ตี้นี้ห่อหุ้มอ็อบเจ็กต์ enumerable (หรือ iterable) เพื่อให้สามารถใช้กับลูป for-range ได้ เวอร์ชันโอเวอร์โหลดนี้สำหรับ Enumerable ที่ไม่มีเมธอด begin(), end() พร้อมอาร์กิวเมนต์ประเภทเป้าหมายสำหรับ (auto& value : IterateOver<SomeType>(enumerable)) |
| std::enable_if\<std::is_scalar\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | คืนค่า hash code ของค่าสเกลาร์ที่ระบุ. |
| std::enable_if<\!std::is_scalar\<T\>::value\&&[System::IsSmartPtr](./issmartptr/)\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | คืนค่า hash code ของอ็อบเจ็กต์ที่ระบุ. |
| std::enable_if\<[System::IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | คืนค่า hash code ของอ็อบเจ็กต์ที่ระบุซึ่งเป็น exception. |
| std::enable_if<\!std::is_scalar\<T\>::value\&&\![System::IsSmartPtr](./issmartptr/)\<T\>::value\&&\![System::IsExceptionWrapper](./isexceptionwrapper/)\<T\>::value, int\>::type [GetHashCode](./gethashcode/)(const T\&) | คืนค่า hash code ของอ็อบเจ็กต์ที่ระบุซึ่งไม่ใช่ smart pointer nor exception. |
| int [GetHashCode](./gethashcode/)(const std::thread::id\&) | การทำเฉพาะสำหรับ std::thread::id; คืนค่า hash code ของอ็อบเจ็กต์เธรดที่ระบุ. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [Cast_noexcept](./cast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | ทำการแคสบนอ็อบเจ็กต์ [SmartPtr](./smartptr/). |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [Cast](./cast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | ทำการแคสบนอ็อบเจ็กต์ [SmartPtr](./smartptr/). |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [DynamicCast_noexcept](./dynamiccast_noexcept/)(const TFrom\&) | การแคสแบบเก่าและล้าสมัย. จะถูกลบในเวอร์ชันอนาคต. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [DynamicCast_noexcept](./dynamiccast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | ทำการแคสต์แบบไดนามิกบนอ็อบเจ็กต์ [SmartPtr](./smartptr/). |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [DynamicCast_noexcept](./dynamiccast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\>) | ทำการแคสต์แบบไดนามิกจาก Objects ไปยังอ็อบเจ็กต์ Exception. |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [DynamicCast](./dynamiccast/)(const TFrom\&) | ทำการแคสต์แบบไดนามิกบนอ็อบเจ็กต์ Exception. |
| std::enable_if<\!std::is_enum\<TTo\>::value\&&\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [DynamicCast](./dynamiccast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | ทำการแคสต์แบบไดนามิกบนอ็อบเจ็กต์ [SmartPtr](./smartptr/). |
| std::enable_if\<std::is_enum\<TTo\>::value, TTo\>::type [DynamicCast](./dynamiccast/)([SmartPtr](./smartptr/)\<TFrom\>) | ถอดกล่อง enum ที่บรรจุด้วยการแคสต์. |
| [CastResult](./castresult/)\<TTo\>::type [DynamicCast](./dynamiccast/)(std::nullptr_t) | ทำการแคสต์แบบไดนามิกของอ็อบเจ็กต์ null. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&\![IsSmartPtr](./issmartptr/)\<TFrom\>::value\&&std::is_convertible\<TTo, TFrom\>::value, TTo\>::type [DynamicCast](./dynamiccast/)(TFrom\&) | ทำการแคสต์แบบไดนามิกบนอ็อบเจ็กต์ที่ไม่ใช่พอยน์เตอร์. |

| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [DynamicCast](./dynamiccast/)([SmartPtr](./smartptr/)\<TFrom\>) | ทำการแคสต์แบบไดนามิกบน Objects ไปยัง Exception objects. |
| std::enable_if\<std::is_pointer\<TTo\>::value\&&std::is_same\<IntPtr, TFrom\>::value, TTo\>::type [DynamicCast](./dynamiccast/)(TFrom) | ทำการแคสต์แบบไดนามิกจาก IntPtr ไปยัง pointer. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [StaticCast_noexcept](./staticcast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | ทำการแคสต์แบบสแตติกบน [SmartPtr](./smartptr/) objects. |
| [CastResult](./castresult/)\<TTo\>::type [StaticCast_noexcept](./staticcast_noexcept/)([WeakPtr](./weakptr/)\<TFrom\> const\&) | ทำการแคสต์แบบสแตติกบน [WeakPtr](./weakptr/) objects. |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [StaticCast_noexcept](./staticcast_noexcept/)(const TFrom\&) | ทำการแคสต์แบบสแตติกบน Exception objects. |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [StaticCast_noexcept](./staticcast_noexcept/)([SmartPtr](./smartptr/)\<TFrom\>) | ทำการแคสต์แบบสแตติกบน Objects ไปยัง Exception objects. |
| std::enable_if<\![IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, typenameCastResult\<TTo\>::type\>::type [StaticCast](./staticcast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | ทำการแคสต์แบบสแตติกบน [SmartPtr](./smartptr/) objects. |
| [CastResult](./castresult/)\<TTo\>::type [StaticCast](./staticcast/)([WeakPtr](./weakptr/)\<TFrom\> const\&) | ทำการแคสต์แบบสแตติกบน [WeakPtr](./weakptr/) objects. |
| [CastResult](./castresult/)\<TTo\>::type [StaticCast](./staticcast/)(std::nullptr_t) | ทำการแคสต์แบบสแตติกของ null objects. |
| std::enable_if\<std::is_arithmetic\<TFrom\>::value, TTo\>::type [StaticCast](./staticcast/)(TFrom) | การทำพิเศษสำหรับประเภทเลขคณิต. |
| std::enable_if\<std::is_same\<TTo, [System::String](./string/)\>::value, TTo\>::type [StaticCast](./staticcast/)(TTo) | ดำเนินการแคสต์จาก [String](./string/) ไปยัง [String](./string/). |
| std::enable_if\<std::is_arithmetic\<TFrom\>::value, TTo\>::type [StaticCast](./staticcast/)(const TFrom *) | การทำพิเศษสำหรับประเภทเลขคณิต. |
| std::enable_if<\!std::is_same\<TFrom, [System::String](./string/)\>::value\&&\![IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&\![IsSmartPtr](./issmartptr/)\<TFrom\>::value\&&\!std::is_arithmetic\<TFrom\>::value, TTo\>::type [StaticCast](./staticcast/)(const TFrom\&) | ทำการแคสต์แบบสแตติกบน non-pointer objects. |
| std::enable_if\<[IsExceptionWrapper](./isexceptionwrapper/)\<TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value\&&(std::is_convertible\<TTo, TFrom\>::value||std::is_base_of\<TTo, TFrom\>::value), TTo\>::type [StaticCast](./staticcast/)(const TFrom\&) | ทำการแคสต์แบบสแตติกบน Exception objects. |
| std::enable_if\<std::is_same\<[System::Object](./object/), TFrom\>::value\&&[IsExceptionWrapper](./isexceptionwrapper/)\<TTo\>::value, TTo\>::type [StaticCast](./staticcast/)([SmartPtr](./smartptr/)\<TFrom\>) | ทำการแคสต์แบบสแตติกบน Objects ไปยัง Exception objects. |
| [CastResult](./castresult/)\<TTo\>::type [ConstCast](./constcast/)(const [SmartPtr](./smartptr/)\<TFrom\>\&) | จบการแคสต์ที่เลิกใช้แล้ว. |
| [CastResult](./castresult/)\<TTo\>::type [ForceStaticCast](./forcestaticcast/)([SmartPtr](./smartptr/)\<TFrom\> const\&) | ทำการแคสต์แบบสแตติกจริงบน [SmartPtr](./smartptr/) objects. |
| [SmartPtr](./smartptr/)\<[Object](./object/)\> [MemberwiseClone](./memberwiseclone/)(T *) | ทำการคัดลอกแบบสมาชิกโดยใช้คอนสตรัคเตอร์คัดลอก. |
| [SharedPtr](./sharedptr/)\<T\> [With](./with/)(const [SharedPtr](./sharedptr/)\<T\>\&, const A\&) | ทำการคลอนเรคคอร์ดอ้างอิงและนำฟังก์เตอร์เริ่มต้นไปใช้กับมัน. |
| T [With](./with/)(const T\&, const A\&) | ทำการคัดลอกเรคคอร์ดโครงสร้างและนำฟังก์เตอร์เริ่มต้นไปใช้กับมัน. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::None, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้การแคสต์อย่างชัดเจน ใช้เมื่อประเภทต้นทางและประเภทผลลัพธ์เหมือนกัน. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Static, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้การแคสต์อย่างชัดเจน ใช้เมื่อจำเป็นต้องทำการแคสต์แบบคล้ายคอนสตรัคเตอร์ง่าย. |
| std::enable_if_t\<Details::CastType\<Source, Result\>[::Exception](./exception/), Result\> [ExplicitCast](./explicitcast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้การแคสต์อย่างชัดเจน ใช้สำหรับ wrapper ของ exception. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::ObjectToException, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้การแคสต์อย่างชัดเจน ใช้สำหรับแคสต์ออบเจกต์เป็น exception. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Pointer, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้การแคสต์อย่างชัดเจน ใช้เมื่อทั้งต้นทางและผลลัพธ์เป็น smart pointers (โดยไม่มี SmartPtr<...> อย่างชัดเจนในประเภทผลลัพธ์). |
| std::enable_if_t\<Details::CastType\<Source, Result\>::RawPointer, typename [CastResult](./castresult/)\<std::remove_pointer_t\<Result\>\>::type\> [ExplicitCast](./explicitcast/)(Source) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้การแคสต์อย่างชัดเจน ใช้เมื่อต้องแคสต์ raw pointer ไปยัง smart pointer. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::PointerToPointer, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้การแคสต์อย่างชัดเจน ใช้เมื่อทั้งต้นทางและผลลัพธ์เป็น smart pointers (โดยมี SmartPtr<...> อย่างชัดเจนในประเภทผลลัพธ์). |
| std::enable_if_t\<Details::CastType\<Source, Result\>::UnboxingToNullable, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้การแคสต์อย่างชัดเจน ใช้สำหรับการ unboxing ออบเจกต์เป็น nullable. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::NullableBoxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้การแคสต์อย่างชัดเจน ใช้เพื่อ box nullable. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::NullableUnboxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้การแคสต์อย่างชัดเจน ใช้สำหรับการ unboxing ออบเจกต์ที่เป็น nullable. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::EnumBoxing, [SmartPtr](./smartptr/)\<[BoxedValueBase](./boxedvaluebase/)\>\> [ExplicitCast](./explicitcast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้การแคสต์อย่างชัดเจน ใช้สำหรับการ box enum. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::HeapifyBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้การแคสต์อย่างชัดเจน ใช้สำหรับคัดลอก value types ไปยัง heap เมื่อ value type ควรอ้างอิงเป็น smart pointer (ใน generic ที่จำกัดด้วย interface type แต่เฉพาะเจาะจงด้วยโครงสร้างที่ทำการ implement interface นี้). |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้การแคสต์อย่างชัดเจน ใช้เพื่อดึง interface จาก value types. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Boxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้การแคสต์อย่างชัดเจน ใช้สำหรับการ box แบบทั่วไป. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::StringBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้การแคสต์อย่างชัดเจน ใช้สำหรับการ box [System::String](./string/). |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceUnboxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้การแคสต์อย่างชัดเจน ใช้สำหรับการ unboxing interfaces. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Unboxing, Result\> [ExplicitCast](./explicitcast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้การแคสต์อย่างชัดเจน ใช้สำหรับการ unboxing แบบทั่วไป. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Null, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้การแคสต์อย่างชัดเจน ใช้สำหรับการแคสต์ nullptr. |
| std::enable_if_t\<Details::CastType\<Source, Result\>**::Array**, typename [CastResult](./castresult/)\<Result\>::type\> [ExplicitCast](./explicitcast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้การแคสต์อย่างชัดเจน ใช้สำหรับการแคสต์ระหว่างอาร์เรย์. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Static, Result\> [AsCast](./ascast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้โอเปอเรเตอร์ 'as' ใช้เมื่อจำเป็นต้องทำการแคสต์แบบคล้ายคอนสตรัคเตอร์ง่าย. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::None, Result\> [AsCast](./ascast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้โอเปอเรเตอร์ 'as' ใช้เมื่อประเภทต้นทางและประเภทผลลัพธ์เหมือนกัน. |
| std::enable_if_t\<Details::CastType\<Source, Result\>[::Exception](./exception/), Result\> [AsCast](./ascast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้โอเปอเรเตอร์ 'as' ใช้สำหรับ wrapper ของ exception. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::ObjectToException, Result\> [AsCast](./ascast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้โอเปอเรเตอร์ 'as' ใช้สำหรับแคสต์ออบเจกต์เป็น exception. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Pointer, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้โอเปอเรเตอร์ 'as' ใช้เมื่อทั้งต้นทางและผลลัพธ์เป็น smart pointers. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::PointerToPointer, Result\> [AsCast](./ascast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้โอเปอเรเตอร์ 'as' ใช้เมื่อทั้งต้นทางและผลลัพธ์เป็น smart pointers (โดยมี SmartPtr<...> อย่างชัดเจนในประเภทผลลัพธ์). |
| std::enable_if_t\<Details::CastType\<Source, Result\>::UnboxingToNullable, Result\> [AsCast](./ascast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้โอเปอเรเตอร์ 'as' ใช้สำหรับการ unboxing ออบเจกต์เป็น nullable. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceUnboxingToNullable, Result\> [AsCast](./ascast/)(const Source\&) | การ unboxing ที่ไม่ถูกต้องไปยังประเภทที่ไม่ใช่ออบเจกต์. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InvalidUnboxing, Result\> [AsCast](./ascast/)(const Source\&) | การ unboxing ที่ไม่ถูกต้องไปยังประเภทที่ไม่ใช่ออบเจกต์. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::NullableBoxing, Result\> [AsCast](./ascast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้โอเปอเรเตอร์ 'as' ใช้สำหรับการ box nullable object. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::InterfaceBoxing, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้โอเปอเรเตอร์ 'as' ใช้สำหรับการ box common object. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Boxing, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้โอเปอเรเตอร์ 'as' ใช้สำหรับการ box common object. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::UnboxingToString, Result\> [AsCast](./ascast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้โอเปอเรเตอร์ 'as' ใช้สำหรับการ unboxing สตริง. |
| std::enable_if_t\<Details::CastType\<Source, Result\>::Null, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้โอเปอเรเตอร์ 'as' ใช้สำหรับการแคสต์ nullptr. |
| std::enable_if_t\<Details::CastType\<Source, Result\>**::Array**, typename [CastResult](./castresult/)\<Result\>::type\> [AsCast](./ascast/)(const Source\&) | ทำการแคสต์ประเภทต้นทางเป็นประเภทผลลัพธ์โดยใช้โอเปอเรเตอร์ 'as' ใช้เพื่อแคสต์ระหว่างอาร์เรย์. |
| static auto [SafeInvoke](./safeinvoke/)(T0\&&, T1\&&) | การดำเนินการแปลโอเปอเรเตอร์ '?.' |
| const [System::TypeInfo](./typeinfo/)\& [ObjectType::GetType< System::String >](./objecttype_dcolon_gettype_less_system_dcolon_string__greater/)() | ทำการแปล typeof() ใช้ overload สำหรับ [String](./string/). |
| const [System::TypeInfo](./typeinfo/)\& [ObjectType::GetType< System::DateTime >](./objecttype_dcolon_gettype_less_system_dcolon_datetime__greater/)() | ทำการแปล typeof() ใช้ overload สำหรับ [DateTime](./datetime/). |
| **bool** [Equals](./equals/)(const TA\&, const TB\&) | กำหนดความเท่ากันของสองค่าโดยใช้ [operator==()](./operator_equal_equal/) กับพวกมัน. |
| **bool** [Equals< float, float >](./equals_less_float,_float__greater/)(const **float**\&, const **float**\&) | การทำพิเศษสำหรับค่า floating point ความแม่นยำเดี่ยว (single-precision) แม้ว่า NaN สองค่าใน floating point จะถูกกำหนดโดย IEC 60559:1989 ให้เปรียบเทียบเป็นไม่เท่ากันเสมอ แต่สัญญาของ [System.Object.Equals](./object/equals/) กำหนดให้การ override ต้องปฏิบัติตามข้อกำหนดของโอเปอเรเตอร์เทียบเท่า ดังนั้น System.Double.Equalsและ System.Single.Equals จะคืนค่า True เมื่อเปรียบเทียบ NaN สองค่า ในขณะที่โอเปอเรเตอร์เท่ากันจะคืนค่า False ตามมาตรฐาน. |
| **bool** [Equals< double, double >](./equals_less_double,_double__greater/)(const **double**\&, const **double**\&) | การทำพิเศษสำหรับค่า floating point ความแม่นยำคู่ (double-precision). |
| std::enable_if_t<\!std::is_floating_point\<TA\>::value\&&\!std::is_floating_point\<TB\>::value, int\> [Compare](./compare/)(const TA\&, const TB\&) | เปรียบเทียบสองค่า. |
| std::enable_if_t\<std::is_floating_point\<TA\>::value\&&std::is_floating_point\<TB\>::value, int\> [Compare](./compare/)(const TA\&, const TB\&) | เปรียบเทียบค่าจุดลอยสองค่า |
| **bool** [IsNaN](./isnan/)(const T\&) | กำหนดว่าค่าที่ระบุเป็นค่า Not-A-Number หรือไม่ |
| **bool** [IsInfinity](./isinfinity/)(const T\&) | กำหนดว่าค่าที่ระบุแสดงถึงค่าไม่มีที่สิ้นสุด |
| **bool** [IsPositiveInfinity](./ispositiveinfinity/)(const T\&) | กำหนดว่าค่าที่ระบุแสดงถึงค่าไม่มีที่สิ้นสุดบวก |
| **bool** [IsNegativeInfinity](./isnegativeinfinity/)(const T\&) | กำหนดว่าค่าที่ระบุแสดงถึงค่าไม่มีที่สิ้นสุดลบ |
| TTo [CheckedCast](./checkedcast/)(TFrom) | กำหนดว่าค่าที่ระบุอยู่ในช่วงค่าของประเภท **TTo** หรือไม่ และหากเป็นเช่นนั้น จะทำการแปลงเป็นประเภท **TTo** |
| [ScopeGuard](./scopeguard/)\<F\> [MakeScopeGuard](./makescopeguard/)(F) | ฟังก์ชันโรงงานที่สร้างอินสแตนซ์ของคลาส ScopedGuard |
| T [setter_wrap](./setter_wrap/)(void(*)(T2), T) | โอเวอร์โหลดสำหรับฟังก์ชันตั้งค่าคงที่พร้อมการแปลงประเภท |
| std::enable_if\<std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_wrap](./setter_wrap/)(Host *const, void(HostSet::*)(T2), T) | โอเวอร์โหลดสำหรับฟังก์ชันตั้งค่าอินสแตนซ์พร้อมการแปลงประเภท |
| T [setter_increment_wrap](./setter_increment_wrap/)(T(*)(), void(*)(T)) | ตัวแปลภาษาแปลงนิพจน์การเพิ่มของ C# ที่มุ่งเป้าไปที่คุณสมบัติของคลาสซึ่งมีตัวตั้งค่าและตัวรับค่ากำหนดไว้ ให้เรียกฟังก์ชันนี้ |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_increment_wrap](./setter_increment_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | ตัวแปลภาษาแปลงนิพจน์การเพิ่มของ C# ที่มุ่งเป้าไปที่คุณสมบัติของคลาสซึ่งมีตัวตั้งค่าและตัวรับค่ากำหนดไว้ ให้เรียกฟังก์ชันนี้ |
| T [setter_post_increment_wrap](./setter_post_increment_wrap/)(T(*)(), void(*)(T)) | ตัวแปลภาษาแปลงนิพจน์การเพิ่มหลังของ C# ที่มุ่งเป้าไปที่คุณสมบัติของคลาสซึ่งมีตัวตั้งค่าและตัวรับค่ากำหนดไว้ ให้เรียกฟังก์ชันนี้ |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_increment_wrap](./setter_post_increment_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | ตัวแปลภาษาแปลงนิพจน์การเพิ่มหลังของ C# ที่มุ่งเป้าไปที่คุณสมบัติของอินสแตนซ์ซึ่งมีตัวตั้งค่าและตัวรับค่ากำหนดไว้ ให้เรียกฟังก์ชันนี้ (โอเวอร์โหลดสำหรับ getter ที่ไม่เป็น const) |
| std::enable_if\<std::is_base_of\<HostConstGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_increment_wrap](./setter_post_increment_wrap/)(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) | ตัวแปลภาษาแปลงนิพจน์การเพิ่มหลังของ C# ที่มุ่งเป้าไปที่คุณสมบัติของอินสแตนซ์ซึ่งมีตัวตั้งค่าและตัวรับค่ากำหนดไว้ ให้เรียกฟังก์ชันนี้ (โอเวอร์โหลดสำหรับ getter ที่เป็น const) |
| T [setter_decrement_wrap](./setter_decrement_wrap/)(T(*)(), void(*)(T)) | ตัวแปลภาษาแปลงนิพจน์การลบก่อนของ C# ที่มุ่งเป้าไปที่คุณสมบัติของคลาสซึ่งมีตัวตั้งค่าและตัวรับค่ากำหนดไว้ ให้เรียกฟังก์ชันนี้ |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_decrement_wrap](./setter_decrement_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | ตัวแปลภาษาแปลงนิพจน์การลบก่อนของ C# ที่มุ่งเป้าไปที่คุณสมบัติของอินสแตนซ์ซึ่งมีตัวตั้งค่าและตัวรับค่ากำหนดไว้ ให้เรียกฟังก์ชันนี้ (โอเวอร์โหลดสำหรับ getter ที่ไม่เป็น const) |
| std::enable_if\<std::is_base_of\<HostConstGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_decrement_wrap](./setter_decrement_wrap/)(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) | ตัวแปลภาษาแปลงนิพจน์การลบก่อนของ C# ที่มุ่งเป้าไปที่คุณสมบัติของอินสแตนซ์ซึ่งมีตัวตั้งค่าและตัวรับค่ากำหนดไว้ ให้เรียกฟังก์ชันนี้ (โอเวอร์โหลดสำหรับ getter ที่เป็น const) |
| T [setter_post_decrement_wrap](./setter_post_decrement_wrap/)(T(*)(), void(*)(T)) | ตัวแปลภาษาแปลงนิพจน์การลบหลังของ C# ที่มุ่งเป้าไปที่คุณสมบัติของคลาสซึ่งมีตัวตั้งค่าและตัวรับค่ากำหนดไว้ ให้เรียกฟังก์ชันนี้ |
| std::enable_if\<std::is_base_of\<HostGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_decrement_wrap](./setter_post_decrement_wrap/)(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) | ตัวแปลภาษาแปลงนิพจน์การลบหลังของ C# ที่มุ่งเป้าไปที่คุณสมบัติของอินสแตนซ์ซึ่งมีตัวตั้งค่าและตัวรับค่ากำหนดไว้ ให้เรียกฟังก์ชันนี้ (โอเวอร์โหลดสำหรับ getter ที่ไม่เป็น const) |
| std::enable_if\<std::is_base_of\<HostConstGet, Host\>::value\&&std::is_base_of\<HostSet, Host\>::value, T\>::type [setter_post_decrement_wrap](./setter_post_decrement_wrap/)(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) | ตัวแปลภาษาแปลงนิพจน์การลบหลังของ C# ที่มุ่งเป้าไปที่คุณสมบัติของอินสแตนซ์ซึ่งมีตัวตั้งค่าและตัวรับค่ากำหนดไว้ ให้เรียกฟังก์ชันนี้ (โอเวอร์โหลดสำหรับ getter ที่เป็น const) |
| std::enable_if<\![IsSmartPtr](./issmartptr/)\<T\>::value, [SmartPtr](./smartptr/)\<T\>\>::type [MakeObject](./makeobject/)(Args\&&...) | สร้างอ็อบเจ็กต์บน heap และคืนค่า shared pointer ไปยังมัน |
| std::enable_if\<[IsSmartPtr](./issmartptr/)\<T\>::value, T\>::type [MakeObject](./makeobject/)(Args\&&...) | สร้างอ็อบเจ็กต์บน heap และคืนค่า shared pointer ไปยังมัน |
| [SmartPtr](./smartptr/)\<X\> [MakeSharedPtr](./makesharedptr/)(X *) | แปลง raw pointer เป็น smart pointer |
| [SmartPtr](./smartptr/)\<X\> [MakeSharedPtr](./makesharedptr/)(const X *) | แปลง raw pointer เป็น smart pointer. โอเวอร์โหลดสำหรับ pointer ที่เป็น const. มีประโยชน์เช่นเมื่อใช้ตัวแปร 'this' ในเมธอด C# ที่แปลเป็น const. |
| [SmartPtr](./smartptr/)\<Y\> [static_pointer_cast](./static_pointer_cast/)([SmartPtr](./smartptr/)\<X\> const\&) | แคส smart pointer โดยใช้ static_cast |
| [SmartPtr](./smartptr/)\<Y\> [dynamic_pointer_cast](./dynamic_pointer_cast/)([SmartPtr](./smartptr/)\<X\> const\&) | แคส smart pointer โดยใช้ dynamic_cast |
| [SmartPtr](./smartptr/)\<Y\> [const_pointer_cast](./const_pointer_cast/)([SmartPtr](./smartptr/)\<X\> const\&) | แคส smart pointer โดยใช้ const_cast |
| T * [get_pointer](./get_pointer/)([System::SmartPtr](./smartptr/)\<T\> const\&) | ดึงอ็อบเจ็กต์ที่อ้างอิงจาก smart pointer |
| std::enable_if<\!System::detail::has_method_get_Count\<From\>::value, [Collections::Generic::ListPtr](../system.collections.generic/listptr/)\<To\>\>::type [CastEnumerableTo](./castenumerableto/)(const From\&) | ทำการแคสอย่างชัดเจนของสมาชิกจากอ็อบเจ็กต์ enumerable ที่ระบุเป็นประเภทอื่น |
| std::enable_if\<System::detail::has_method_get_Count\<From\>::value, [Collections::Generic::ListPtr](../system.collections.generic/listptr/)\<To\>\>::type [CastEnumerableTo](./castenumerableto/)(const From\&) | ทำการแคสอย่างชัดเจนของสมาชิกจากอ็อบเจ็กต์ enumerable ที่ระบุเป็นประเภทอื่น |
| std::enable_if_t\<[System::IsSmartPtr](./issmartptr/)\<From\>::value, [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<To\>\>\> [StaticCastArray](./staticcastarray/)(const [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<From\>\>\&) | ทำการแคสของสมาชิกในอาร์เรย์ที่ระบุเป็นประเภทอื่น การเขียนทับสำหรับกรณีที่ From เป็นอ็อบเจ็กต์ [SmartPtr](./smartptr/) |
| std::enable_if_t<\![System::IsSmartPtr](./issmartptr/)\<From\>::value\&&[System::IsBoxable](./isboxable/)\<From\>::value\&&std::is_same\<To, [System::SharedPtr](./sharedptr/)\<[Object](./object/)\>\>::value, [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<To\>\>\> [StaticCastArray](./staticcastarray/)(const [System::SharedPtr](./sharedptr/)\<[System::Array](./array/)\<From\>\>\&) | ทำการแคสของสมาชิกในอาร์เรย์ที่ระบุเป็นประเภทอื่น การเขียนทับสำหรับกรณีที่ From เป็น Boxable และ To เป็น [Object](./object/)[] |
| [SharedPtr](./sharedptr/)\<[Array](./array/)\<To\>\> [DynamicCastArray](./dynamiccastarray/)(const [SharedPtr](./sharedptr/)\<[Array](./array/)\<From\>\>\&) | ทำการแคสของสมาชิกในอาร์เรย์ที่ระบุเป็นประเภทอื่น |
| std::istream\& [operator>>](./operator_greater_greater/)(std::istream\&, [String](./string/)\&) | ดึงสตริงจาก input stream โดยใช้การเข้ารหัส UTF-8 |
| std::wistream\& [operator>>](./operator_greater_greater/)(std::wistream\&, [String](./string/)\&) | ดึงสตริงจาก input stream |
| [TaskPtr](./taskptr/) [MakeAsync](./makeasync/)(const Details::AsyncFunction\&) |  |
| [RTaskPtr](./rtaskptr/)\<T\> [MakeAsync](./makeasync/)(const Details::ResultAsyncFunction\<T\>\&) |  |
| [Threading::Tasks::ResultValueTask](../system.threading.tasks/resultvaluetask/)\<T\> [MakeValueAsync](./makevalueasync/)(const Details::ResultAsyncFunction\<T\>\&) |  |
| [Threading::Tasks::ValueTask](../system.threading.tasks/valuetask/) [MakeValueAsync](./makevalueasync/)(const Details::AsyncFunction\&) |  |
| [ValueTuple](./valuetuple/)\<Args...\> [MakeTuple](./maketuple/)(Args...) | สร้าง tuple บน stack |
| [ValueTuple](./valuetuple/)\<Args...\> [TieTuple](./tietuple/)(Args\&&...) | สร้าง tuple ที่ผูกกับค่าบางค่า |
| **bool** [is_vp_test](./is_vp_test/)(const ::testing::TestInfo *) |  |
| **bool** [is_parametrized_test](./is_parametrized_test/)(const ::testing::TestInfo *) |  |
| std::string [ForEachMemberGVName](./foreachmembergvname/)() |  |

## Enums

| Enum | Description |
| --- | --- |
| [Base64FormattingOptions](./base64formattingoptions/) | การนับค่าที่มีค่าแสดงรูปแบบต่าง ๆ ของข้อมูลที่เข้ารหัสแบบ base-64 |
| [DateTimeKind](./datetimekind/) | ค่าการนับที่แสดงประเภทของวันและเวลา |
| [DayOfWeek](./dayofweek/) | การนับที่แสดงวันของสัปดาห์ |
| [EnvironmentVariableTarget](./environmentvariabletarget/) | ระบุตำแหน่งของตัวแปรสภาพแวดล้อม |
| [MidpointRounding](./midpointrounding/) | ระบุพฤติกรรมของฟังก์ชันการปัดเศษ |
| [PlatformID](./platformid/) | แสดงแพลตฟอร์มของระบบปฏิบัติการ |
| [SmartPtrMode](./smartptrmode/) | [SmartPtr](./smartptr/) ประเภทตัวชี้: weak หรือ shared. กำหนดว่าตัวชี้จะถูกนับหรือไม่เมื่อพิจารณาว่าจะลบอ็อบเจ็กต์หรือไม่ |
| [StringSplitOptions](./stringsplitoptions/) | กำหนดพฤติกรรมการแบ่งสตริง |
| [StringComparison](./stringcomparison/) | กำหนดรูปแบบการเปรียบเทียบสตริง |
| [TypeCode](./typecode/) | แสดงประเภทของอ็อบเจ็กต์ |
| [UriKind](./urikind/) | แสดงประเภทของ URI |
| [UriComponents](./uricomponents/) | แสดงส่วนประกอบของ URI |
| [UriFormat](./uriformat/) | ระบุวิธีการ escape ของ URI |
| [UriHostNameType](./urihostnametype/) | แสดงประเภทของชื่อโฮสต์ |
| [UriPartial](./uripartial/) | แสดงส่วนต่าง ๆ ของ URI สำหรับเมธอด [Uri.GetLeftPart](./uri/getleftpart/) |

## Typedefs

| Typedef | Description |
| --- | --- |
| [IFormatProviderPtr](./iformatproviderptr/) | นามแฝงสำหรับ smart pointer ที่ชี้ไปยังอินสแตนซ์ของคลาส [System::IFormatProvider](./iformatprovider/) |
| [DecoderFallbackPtr](./decoderfallbackptr/) | นามแฝงสำหรับ smart pointer ที่ชี้ไปยังอินสแตนซ์ของคลาส [System::Text::DecoderFallback](../system.text/decoderfallback/) |
| [DecoderFallbackBufferPtr](./decoderfallbackbufferptr/) | นามแฝงสำหรับ smart pointer ที่ชี้ไปยังอินสแตนซ์ของคลาส [System::Text::DecoderFallbackBuffer](../system.text/decoderfallbackbuffer/) |
| [DecoderReplacementFallbackPtr](./decoderreplacementfallbackptr/) | นามแฝงสำหรับ smart pointer ที่ชี้ไปยังอินสแตนซ์ของคลาส [System::Text::DecoderReplacementFallback](../system.text/decoderreplacementfallback/) |
| [EncoderFallbackPtr](./encoderfallbackptr/) | นามแฝงสำหรับ smart pointer ที่ชี้ไปยังอินสแตนซ์ของคลาส [System::Text::EncoderFallback](../system.text/encoderfallback/) |
| [EncoderFallbackBufferPtr](./encoderfallbackbufferptr/) | นามแฝงสำหรับ smart pointer ที่ชี้ไปยังอินสแตนซ์ของคลาส [System::Text::EncoderFallbackBuffer](../system.text/encoderfallbackbuffer/) |
| [EncoderPtr](./encoderptr/) | นามแฝงสำหรับ smart pointer ที่ชี้ไปยังอินสแตนซ์ของคลาส [System::Text::Encoder](../system.text/encoder/) |
| [DecoderPtr](./decoderptr/) | นามแฝงสำหรับ smart pointer ที่ชี้ไปยังอินสแตนซ์ของคลาส [System::Text::Decoder](../system.text/decoder/) |
| [EncoderReplacementFallbackBufferPtr](./encoderreplacementfallbackbufferptr/) | นามแฝงสำหรับ smart pointer ที่ชี้ไปยังอินสแตนซ์ของคลาส [System::Text::EncoderReplacementFallbackBuffer](../system.text/encoderreplacementfallbackbuffer/) |
| [EncoderReplacementFallbackPtr](./encoderreplacementfallbackptr/) | นามแฝงสำหรับ smart pointer ที่ชี้ไปยังอินสแตนซ์ของคลาส [System::Text::EncoderReplacementFallback](../system.text/encoderreplacementfallback/) |
| [EncodingPtr](./encodingptr/) | นามแฝงสำหรับ smart pointer ที่ชี้ไปยังอินสแตนซ์ของคลาส [System::Text::Encoding](../system.text/encoding/) |
| [EncodingInfoPtr](./encodinginfoptr/) | นามแฝงสำหรับ smart pointer ที่ชี้ไปยังอินสแตนซ์ของคลาส [System::Text::EncodingInfo](../system.text/encodinginfo/) |
| [StreamPtr](./streamptr/) | นามแฝงสำหรับ smart pointer ที่ชี้ไปยังอินสแตนซ์ของคลาส [System::IO::Stream](../system.io/stream/) |
| [FileStreamPtr](./filestreamptr/) | นามแฝงสำหรับ smart pointer ที่ชี้ไปยังอินสแตนซ์ของคลาส [System::IO::FileStream](../system.io/filestream/) |
| [MemoryStreamPtr](./memorystreamptr/) | นามแฝงสำหรับ smart pointer ที่ชี้ไปยังอินสแตนซ์ของคลาส [System::IO::MemoryStream](../system.io/memorystream/) |
| [StreamReaderPtr](./streamreaderptr/) | นามแฝงสำหรับ smart pointer ที่ชี้ไปยังอินสแตนซ์ของคลาส [System::IO::StreamReader](../system.io/streamreader/) |
| [StreamWriterPtr](./streamwriterptr/) | นามแฝงสำหรับ smart pointer ที่ชี้ไปยังอินสแตนซ์ของคลาส [System::IO::StreamWriter](../system.io/streamwriter/) |
| [FileInfoPtr](./fileinfoptr/) | นามแฝงสำหรับ smart pointer ที่ชี้ไปยังอินสแตนซ์ของคลาส [System::IO::FileInfo](../system.io/fileinfo/) |
| [FileSystemInfoPtr](./filesysteminfoptr/) | นามแฝงสำหรับ smart pointer ที่ชี้ไปยังอินสแตนซ์ของคลาส [System::IO::FileSystemInfo](../system.io/filesysteminfo/) |
| [DirectoryInfoPtr](./directoryinfoptr/) | นามแฝงสำหรับ smart pointer ที่ชี้ไปยังอินสแตนซ์ของคลาส [System::IO::DirectoryInfo](../system.io/directoryinfo/) |
| [TaskPtr](./taskptr/) | นามแฝงสำหรับ smart pointer ที่ชี้ไปยังอินสแตนซ์ของคลาส [System::Threading::Tasks::Task](../system.threading.tasks/task/) |
| [RTaskPtr](./rtaskptr/) | นามแฝงสำหรับ smart pointer ที่ชี้ไปยังอินสแตนซ์ของคลาส [System::Threading::Tasks::ResultTask](../system.threading.tasks/resulttask/) |
| [FunctionPtr](./functionptr/) | นามแฝงสำหรับประเภทฟังก์ชันที่มีการเรียกแบบค่าเริ่มต้น |
| [Action](./action/) | ประเภท delegate ที่อ้างอิงเมธอดที่ไม่มีค่ากลับ |
| [AggregateException](./aggregateexception/) |  |
| [ByteArrayPtr](./bytearrayptr/) | นามแฝงสำหรับอ็อบเจ็กต์ smart pointer ที่ชี้ไปยังอาร์เรย์ของจำนวนเต็มบวก 8-บิต |
| [AsyncCallback](./asynccallback/) | ประเภท delegate ที่แสดงเมธอดที่จะถูกเรียกเมื่อการดำเนินการแบบอะซิงโครนัสเสร็จสิ้น |
| [BadImageFormatException](./badimageformatexception/) | ข้อยกเว้นที่ถูกโยนเมื่อไฟล์อิมเมจของไลบรารีเชื่อมต่อแบบไดนามิก (DLL) หรือโปรแกรมปฏิบัติการเป็นไฟล์ที่ไม่ถูกต้อง ไม่ควรห่ออ็อบเจ็กต์ BadImageFormatException ไว้ใน [System::SmartPtr](./smartptr/) |
| [Converter](./converter/) | แสดงตัวชี้ไปยังเอนทิตีที่สามารถเรียกใช้ได้ที่รับอาร์กิวเมนต์เดียวของชนิด **TInput** และคืนค่าชนิด **TOutput** |
| [Event](./event/) | แสดงอีเวนต์ - กลไกที่ผู้สมัครรับข้อมูลจะได้รับการแจ้งเมื่อเกิดเหตุการณ์ที่สนใจโดยการเรียก delegate |
| [EventArgsPtr](./eventargsptr/) | smart pointer ไปยังอินสแตนซ์ของคลาส [EventArgs](./eventargs/) |
| [EventHandler](./eventhandler/) | แสดงเมธอดที่ตอบสนองและประมวลผลอีเวนต์ ประเภทนี้ควรจัดสรรบน stack และส่งต่อให้ฟังก์ชันโดยค่า หรือโดยอ้างอิง ไม่ควรใช้คลาส [System::SmartPtr](./smartptr/) เพื่อจัดการอ็อบเจ็กต์ประเภทนี้ |
| [ExceptionPtr](./exceptionptr/) | นามแฝงประเภทที่ใช้โดยตัวห่อข้อยกเว้น |
| [Exception](./exception/) | นามแฝงที่จะใช้แทน Details::Exception |
| [SystemException](./systemexception/) |  |
| [ApplicationException](./applicationexception/) |  |
| [InvalidOperationException](./invalidoperationexception/) |  |
| [InvalidProgramException](./invalidprogramexception/) |  |
| [InvalidTimeZoneException](./invalidtimezoneexception/) |  |
| [TimeZoneNotFoundException](./timezonenotfoundexception/) |  |
| [ObjectDisposedException](./objectdisposedexception/) |  |
| [NotImplementedException](./notimplementedexception/) |  |
| [NotSupportedException](./notsupportedexception/) |  |
| [PlatformNotSupportedException](./platformnotsupportedexception/) |  |
| [ArgumentException](./argumentexception/) |  |
| [ArgumentNullException](./argumentnullexception/) |  |
| [ArgumentOutOfRangeException](./argumentoutofrangeexception/) |  |
| [FormatException](./formatexception/) |  |
| [UriFormatException](./uriformatexception/) |  |
| [ArithmeticException](./arithmeticexception/) |  |
| [OverflowException](./overflowexception/) |  |
| [DivideByZeroException](./dividebyzeroexception/) |  |
| [OutOfMemoryException](./outofmemoryexception/) |  |
| [IndexOutOfRangeException](./indexoutofrangeexception/) |  |
| [RankException](./rankexception/) |  |
| [InvalidCastException](./invalidcastexception/) |  |
| [NullReferenceException](./nullreferenceexception/) |  |
| [UnauthorizedAccessException](./unauthorizedaccessexception/) |  |
| [MemberAccessException](./memberaccessexception/) |  |
| [MethodAccessException](./methodaccessexception/) |  |
| [OperationCanceledException](./operationcanceledexception/) |  |
| [StackOverflowException](./stackoverflowexception/) |  |
| [TimeoutException](./timeoutexception/) |  |
| [ExecutionEngineException](./executionengineexception/) |  |
| [TypeInitializationException](./typeinitializationexception/) |  |
| [DataMisalignedException](./datamisalignedexception/) |  |
| [IAsyncResultPtr](./iasyncresultptr/) | ตัวชี้แบบแชร์ไปยัง [IAsyncResult](./iasyncresult/). |
| [MakeConstRef_t](./makeconstref_t/) | ประเภทช่วยเหลือสำหรับตัวปรับแต่ง [MakeConstRef](./makeconstref/). |
| [Predicate](./predicate/) | แสดงถึงตัวชี้ไปยัง predicate - เอนทิตี้ที่สามารถเรียกใช้ได้ซึ่งรับอาร์กิวเมนต์เดียวและคืนค่า bool. |
| [ArrayPtr](./arrayptr/) | นามแฝงสำหรับประเภท 'pointer to array'. |
| [SharedPtr](./sharedptr/) | นามแฝงสำหรับ smart pointer ที่ใช้กันอย่างแพร่หลายในไลบรารี. |
| [StringComparerPtr](./stringcomparerptr/) | นามแฝงสำหรับตัวชี้แบบแชร์ไปยังอินสแตนซ์ของคลาส [StringComparer](./stringcomparer/). |
| [TimeZonePtr](./timezoneptr/) | ตัวชี้แบบแชร์ไปยังอินสแตนซ์ของคลาส [TimeZone](./timezone/). |
| [TimeZoneInfoPtr](./timezoneinfoptr/) | นามแฝงสำหรับตัวชี้แบบแชร์ไปยังอินสแตนซ์ของคลาส [TimeZoneInfo](./timezoneinfo/). |