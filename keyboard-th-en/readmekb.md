# ตัวอย่าง การตั้งค่าแป้นพิมพ์ ไทย-อังกฤษ บน Raspberry Pi  
ติดตั้ง ไทย/อังกฤษ และกดเปลี่ยนภาษาด้วย [Alt+Shift]  
แก้ไขที่สามไฟล์ข้างล่าง โดยใช้คำสั่ง `$ sudo geany <ชื่อไฟล์>` ดังต่อไปนี้    
  
`$ sudo geany /etc/default/keyboard `  
โดยแก้ไขตาม https://github.com/sangsiri/my-rpi3-setup/blob/master/keyboard 
แล้วบันทึกออกจากโปรแกรม geany 
  
`$ sudo geany /etc/xdg/lxsession/LXDE-pi/autokey.sh `    
โดยแก้ไขตาม https://github.com/sangsiri/my-rpi3-setup/blob/master/autokey.sh  
แล้วบันทึกออกจากโปรแกรม geany
  
`$ sudo geany /etc/xdg/lxsession/LXDE-pi/autostart `  
โดยแก้ไขตาม https://github.com/sangsiri/my-rpi3-setup/blob/master/lxkeymap.cfg  
แล้วบันทึกออกจากโปรแกรม geany
  
ที่มา:
* https://wiki.debian.org/Keyboard
