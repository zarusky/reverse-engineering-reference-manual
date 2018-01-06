## *<p align='center'>.tools</p>*

<div align='center'> 
<img src="https://github.com/yellowbyte/reverse-engineering-reference-manual/blob/reorganize/images/tools/tools.jpg" width="500" height="430"> 
<p align='center'><sub><strong>drawing by <a href="http://www.leejohnphillips.com/">Lee John Phillips</a></strong></sub></p>
</div>

__The Power Of Two__
* When reversing a target, you will likely run various basic static analysis, dynamic analysis, and/or automation tools to identify point of interests for further manual analysis. Once you identified all the point of interests, the majority of your time will be spent inside a disassembler and a debugger to try to figure out if any of those point of interests leads you closer to your goal (e.g. finding exploitable bugs). As a result, at least __know how to use a disassembler and a debugger well__.

__Be Cautious...__
* Never be too reliant on any one tool. For every popular tool, depending on the tool's usage, there are ways to detect its presence (e.g. if gdb is detected, divert from normal execution), hide certain program properties from it, or make it not function properly. 

---
### *<p align='center'> section overview </p>*
---
* [IDA Tips](IDA_Tips.md)
  * [Addresses Shown In IDA](IDA_Tips.md#-addresses-shown-in-ida-)
  * [Import Address Table (IAT)](IDA_Tips.md#-import-address-table-iat-)
  * [Saving Memory Snapshot From Your Debugger Session](IDA_Tips.md#-saving-memory-snapshot-from-your-debugger-session-)
  * [Useful Shortcuts](IDA_Tips.md#-useful-shortcuts-)
* [GDB Tips](GDB_Tips.md)
  * [Changing Default Settings](GDB_Tips.md#-changing-default-settings-)
  * [User Inputs](GDB_Tips.md#-user-inputs-)
  * [Automation](GDB_Tips.md#-automation-)
  * [Ways To Pause Debuggee](GDB_Tips.md#-ways-to-pause-debuggee-)
  * [Useful Commands](GDB_Tips.md#-useful-commands-)

---
### *<p align='center'> further readings </p>*
---
*work in progress...*

#
<p align='center'><a href="/contents/general-knowledge/int_0x7374617274.md">int_0x7374617274</a> | <a href="/contents/tools/IDA_Tips.md">IDA_Tips</a></p>