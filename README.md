# MybatisPlus + POI 异步导出方案门面
> 利用MybatisPlus的自动分页参数配置来完成功能

**场景**

1. 普通的 N 条数据单页导出（N最好小于十万）
2. 数据导出时按数据行进行合并单元格
3. 大量数据导出，同一个Excel文件分多工作表进行写入
4. 针对复杂巨型数据的游标与数据加工处理