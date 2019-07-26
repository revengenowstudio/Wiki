## 复仇时刻RN 0.99.G0726P更新说明
* 重构了RE(reconnection error)收集机制的文件写入，恢复了旧版方式的内容写入
* 本次启动器更新将会尝试自动给Win7 及以上用户的 RA2MD.EXE YURI.EXE RunRN.EXE GameRN.EXE GameMD.EXE获取管理员权限，并给GameRN.EXE GameMD.EXE设置16色
* [Bug#58]光棱坦克反甲能力下调至原来的一半（恢复到原版YR数值），移动攻击能力得到保留
* [Bug#132]英国观察员召唤的智能炸弹可以被铁幕和立场护盾影响，这将不再被允许
* [Bug#123]尤里空投炸弹之前可以被神经突击毒气影响，现在不会再受到影响
* [Adjustment#108]法国气象塔补上了雷暴技能的环境云层动画，同时修正了闲置动画不连续的问题
* [Bug#195]古巴自爆飞机出厂时会出现在盟军的停机平台上，而不受停机平台机位控制，现在盟军停机平台不再允许生产出自爆飞机
* 修正了内测盟军第三关任务目标一完成后，援军中的圣骑士战甲无法正确登场的问题
* 修正了有时AI的特殊小队会导致游戏崩溃的问题（建筑目标编写错误）
* 针对AI工程师小队进行微调，增加了AI消除冗余工程师单位的措施
* 对苏军第一关任务的AI小队进行了调整

***

## 复仇时刻RN 0.99.G0615P3更新说明
* 修正了RE(reconnection error)收集机制的文件写入错误

***
## 复仇时刻RN 0.99.G0615P2更新说明

* [Bug#188]联机时古巴的自爆飞机被击落会造成崩溃和断线
* 加强了对RE(reconnection error)问题的信息收集机制

***

## 复仇时刻RN 0.99.G0615P1更新说明

* [Bug#167]修正了苏系阵营的国家存在核能反应堆时，被摧毁无法判定该所属方失败的Bug

[Bug#167]:https://github.com/Zero-Fanker/RN_All_Issues/issues/167
[Bug#188]:https://github.com/Zero-Fanker/RN_All_Issues/issues/188
[Bug#58]:https://github.com/Zero-Fanker/RN_All_Issues/issues/58
[Bug#132]:https://github.com/Zero-Fanker/RN_All_Issues/issues/132
[Bug#123]:https://github.com/Zero-Fanker/RN_All_Issues/issues/123
[Bug#195]:https://github.com/Zero-Fanker/RN_All_Issues/issues/195
[Adjustment#108]:https://github.com/Zero-Fanker/RN_Internal_Issues/issues/108

***

## 复仇时刻RN 0.99.G0615P更新说明（编写中）
本次更新的重点内容（包括但不限于）：
1. 启动器显示版本号，支持自动更新
2. 修复若干F1028版本的任务无法通关问题
3. 新增法国气象塔建筑（屏蔽粉碎大炮）
4. 古巴kbfz改为伪装渗透单位，新增荣耀战士
5. 全局AI重写(欢迎挑战!)
6. 开放主线任务盟军第三关(非最终版本)