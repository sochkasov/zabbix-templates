# zabbix-templates
Шаблон для серверов Dell PowerEdge
Сделано на основании iDRAC MIB ver.3.0


Спасибо за оригинал шаблона сеньеру Jason (https://www.zabbix.com/forum/showpost.php?p=141822&postcount=8)

В таблицу преобразования значений нужно добавить следующие данные:

```Dell Open Manage System Status

1 ⇒ Other
2 ⇒ Unknown
3 ⇒ OK
4 ⇒ NonCritical
5 ⇒ Critical
6 ⇒ NonRecoverable

DellPowerState

1 ⇒ Other
2 ⇒ Unknown
3 ⇒ Off
4 ⇒ On

DellDracDiskState

1 ⇒ Unknown
2 ⇒ Ready
3 ⇒ Online
4 ⇒ Foreign
5 ⇒ Offline
6 ⇒ Blocked
7 ⇒ Failed
8 ⇒ Non-RAID
9 ⇒ Removed

DellRaidLevel

1 ⇒ Not known
2 ⇒ RAID-0
3 ⇒ RAID-1
4 ⇒ RAID-5
5 ⇒ RAID-6
6 ⇒ RAID-10
7 ⇒ RAID-50
8 ⇒ RAID-60
9 ⇒ Concatenated RAID 1
10 ⇒ Concatenated RAID 5

DellRaidVolumeState

1 ⇒ Unknown
2 ⇒ Online
3 ⇒ Failed
4 ⇒ Degraded

Dell_PSU_SensorState

1 ⇒ Presence Detected
2 ⇒ PS Failure
4 ⇒ Predictuve Failure
8 ⇒ PS AC lost
16 ⇒ AC lost or out of range
32 ⇒ AC out of range but still present

Dell PSU State Settings

1 ⇒ Unknown
2 ⇒ Online (state disabled)
4 ⇒ not Ready
8 ⇒ Fan Failure
10 ⇒ Online and Fan Failure
16 ⇒ On
242 ⇒ Online and OK

Dell_CPU_StatusState

1 ⇒ other
2 ⇒ unknown
3 ⇒ enabled
4 ⇒ userDisabled
5 ⇒ biosDisabled
6 ⇒ idle
```
