��ӭʹ��Arduino-Lite, ����һ������AVR�豸���������Ҹ�Ч�����п⡣
Arduino-Lite�ǻ���Arduino��Ŀ�Ĺ�����������վ��www.arduino.cc

Arduino-Lite��RoboPeak�������Ŷ�(www.RoboPeak.com)�ڲ�����ʹ�õ����п⣬
���Ǻ����ҽ�������п�������ʹ�á�

����Ŀ��վ:       http://code.google.com/p/arduino-lite
RoboPeak�Ŷ���վ: http://www.robopeak.com

-------------------------
 �״�ʹ��
-------------------------
���״��ڼ������ʹ�ø����п�ʱ(�մ�SVN��check-out���Ǹմ����ص�������н�
ѹ��)����������²���

 a. ȷ����ǰ�Ĳ���ϵͳ�Ǳ�Arduino-Lite֧�ֵ� (��� ֧�ֵ�ƽ̨)
 b. ��������ĸ�Ŀ¼��ִ�� buildenv.cmd ��ע����ű�
 c. ���ýű����ִ�к�Arduino-Lite�Ϳ���ʹ����

Arduino-Lite�����Ұ����ģ�����ζ����������ϵͳ�а�װ�κζ����������Ϳ⡣
(�ǵģ�WINAVRҲ�Ѿ�������Arduino-Lite����)��

-------------------------
 ֧�ֵ�ƽ̨
-------------------------
Arduino-Lite��Դ�����ǿ���������ƽ̨��ʹ�õ�(Linux, MacOS, Win32)����������
����ϵͳĿǰ����֧��Win32ƽ̨��

Ŀǰ����Windowsƽ̨�Ѿ�ͨ����֤��
<> Windows XP 32λ�汾
<> Windows Vista 32λ �� 64λ �汾
<> Windows 7 32λ �� 64λ �汾

-------------------------
 ����һ���¹���
-------------------------
����Arduino-Lite�Ĺ��̿���ֱ�Ӵ�λ��<Arduino-lite home>/sketch/template.zip
��ģ�崴����

�밴�����²��贴�����Ĺ���:
1) ��template.zip��ѹ����Ŀ¼<Arduino-lite home>/sketch
2) ��ȷ����ѹ�����Ŀ¼�ṹ�������ģ�
   <Arduino-lite home>/sketch/template/build.cmd
3) ��template�ļ���������������ϣ���Ĺ������֣�����: helloAVR
4) �����һ���µĹ����Ѿ�����

-------------------------
 ����һ������
-------------------------
1) ���빤���ļ���(����:helloAVR)��ִ��Ŀ¼�е�������ű�launchsh.cmd
2) ���������ն��¼���: make <�س�>
3) ��ʱ����ʼ�Ե�ǰ���̽��б��룬���һ��˳������������
<project_folder>/build/Ŀ¼���ҵ�hex/elf�ļ���

-------------------------
 �������ĵ����ֲ�?
-------------------------
��ص�ʹ���ֲ���ĵ���������������:

  Arduino-Lite�ص��ԭ�����:
         http://www.robopeak.net/blog/?p=42
  Arduino-Lite�Ļ�ȡ��ʹ��:
         http://www.robopeak.net/blog/?p=70
  Arduino-Lite�����ֲ�Ϳ����ο�:
         http://www.robopeak.net/blog/?p=107
  ��Ŀ��ҳ: 
         http://code.google.com/p/arduino-lite

���⣬��������RoboPeak�Ŷ���վ(http://www.robopeak.com)���ҵ������������Ϣ��

Arduino-Lite�͹ٷ���Arduino������ƣ����ᷢ�ֺܶຯ�����÷�ʽ��������ġ�
��ˣ�Arduino�ٷ���վ�е��ĵ�Ҳ�����á�

---------------------------
 ���õ�make����
---------------------------
�������:
<> make/make all
   ���뵱ǰ����
<> make clean
   ����ϴα���Ľ��

оƬ����/���
<> make upload
   ��hex���������ϴ���Ŀ��AVRоƬ��(ͨ��STK500v2Э���bootloader)
<> make usbupload
   ��hex����USB�ϴ���Ŀ��AVRоƬ��(ͨ��HidBootloader)
<> make burn
   ��hexͨ��RoboPeak USB Connector�����(����Avr-doper�����豸)��д��Ŀ��AVRоƬ
<> make erase
   ͨ��RoboPeak USB Connector�����(����Avr-doper�����豸)����Ŀ��AVRоƬ������
<> make fuse
   ͨ��RoboPeak USB Connector�����(����Avr-doper�����豸)��Ŀ��оƬ������˿λ
<> make lock
   ͨ��RoboPeak USB Connector�����(����Avr-doper�����豸)��Ŀ��оƬ����Lock bit

��������͵���
<> make dump
   �����������elf(*.elf)�ļ��������AVR������
<> make dumpobj
   �����������Ŀ���ļ�(*.o)�������AVR������


---------------------------
 ��ϵ����
---------------------------
����Ŀ�ĳ�ʼ������Ա��Shikai Chen (www.csksoft.net)���������ʣ���E-mail:
 csk@live.com