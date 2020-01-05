# activiti-engine

## package

- `cfg`: 配置文件相关
- `compatibility`: 兼容性相关，activiti 5 升级 activiti 6 中不兼容的部分做适配
- `debug`: 调试相关
- `delegate`: 指定的节点（ServiceTask）,都要实现这个里面的
- `event`: 事件和监听机制
- `form`: 工作流和表单，通用表单
- `history`: 工作流大量历史数据，每个节点的记录
- `identity`: 个人身份校验，和身份认证相关
- `impl`: 具体实现
- `logging`: 日志相关
- `management`: 管理相关
- `parse`: 解析工作（xml）
- `query`: 数据库操作，定义了一些抽象的查询接口
- `repository`: 流程部署到数据的过程，部署、配置文件、二进制文件
- `runtime`: 和`history`有一定关系，运行中使用runtime,结束后移动到history中
- `task`: 每一个流程节点流转到人员处理，需要一个task来处理
- `test`: 一些测试以及帮助类
- `*Exception`: 异常相关
- `*Service`: 很多基础的service