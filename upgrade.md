#V2.0稳定版  v2.0-bate
## 主要功能修改
* 完成功能测试
* 新增事务支持
* 修复字段bug
* 修复通用模型bug

## 升级须知

该版本为所有数据操作都进行了事务处理。对表结构进行了修改，因此新增数据库结构变更脚本来执行数据结构变更。

* 数据结构变更：升级版本此版本请执行 ` php  /Public/shell.php  Shell/Index/v2_0_bate ` 来更新数据库结构。



# v2.0 通用模型版  v2.0-alpha
    升级TP系统到3.2.3。添加通用模型、修复因升级导致的系统bug、调整系统功能、优化系统流程。