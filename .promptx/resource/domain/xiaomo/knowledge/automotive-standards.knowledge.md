<knowledge>
# 汽车行业标准知识体系

## 功能安全标准体系

### ISO 26262道路车辆功能安全
```mermaid
graph TD
    A[ISO 26262标准结构] --> B[Part 1: 词汇]
    A --> C[Part 2: 功能安全管理]
    A --> D[Part 3: 概念阶段]
    A --> E[Part 4: 系统级产品开发]
    A --> F[Part 5: 硬件级产品开发]
    A --> G[Part 6: 软件级产品开发]
    A --> H[Part 7: 生产/运行/服务/报废]
    A --> I[Part 8: 支持过程]
    A --> J[Part 9: ASIL/SIL导向分析]
    A --> K[Part 10: 指南]
    A --> L[Part 11: 半导体应用指南]
    A --> M[Part 12: 摩托车应用]
```

### ASIL安全完整性等级
```mermaid
graph LR
    A[ASIL等级] --> B[ASIL A]
    A --> C[ASIL B]
    A --> D[ASIL C]
    A --> E[ASIL D]
    A --> F[QM]
    
    B --> B1[最低安全要求<br/>简单安全措施<br/>基础验证]
    
    C --> C1[中等安全要求<br/>适度安全措施<br/>增强验证]
    
    D --> D1[较高安全要求<br/>强化安全措施<br/>严格验证]
    
    E --> E1[最高安全要求<br/>全面安全措施<br/>最严验证]
    
    F --> F1[非安全相关<br/>质量管理<br/>标准流程]
```

### ISO 21448预期功能安全SOTIF
```mermaid
graph TD
    A[SOTIF标准] --> B[范围定义]
    A --> C[验证方法]
    A --> D[确认方法]
    
    B --> B1[系统局限性]
    B --> B2[可预见误用]
    B --> B3[性能不足]
    
    C --> C1[场景识别]
    C --> C2[测试验证]
    C --> C3[仿真验证]
    
    D --> D1[现实世界测试]
    D --> D2[数据驱动论证]
    D --> D3[统计论证方法]
```

## 网络安全标准

### ISO/SAE 21434汽车网络安全
```mermaid
flowchart TD
    A[ISO 21434网络安全] --> B[组织网络安全管理]
    A --> C[项目相关网络安全管理]
    A --> D[连续网络安全活动]
    A --> E[风险评估方法]
    A --> F[网络安全监控与响应]
    
    B --> B1[网络安全策略]
    B --> B2[网络安全文化]
    B --> B3[能力建设]
    
    C --> C1[网络安全概念]
    C --> C2[产品开发]
    C --> C3[网络安全验证]
    C --> C4[网络安全确认]
    
    D --> D1[运行监控]
    D --> D2[事件响应]
    D --> D3[漏洞管理]
    
    E --> E1[威胁建模TARA]
    E --> E2[风险处理]
    E --> E3[残余风险评估]
```

### UNECE WP.29网络安全法规
```mermaid
graph LR
    A[UN R155/R156法规] --> B[R155网络安全]
    A --> C[R156软件更新]
    
    B --> B1[网络安全管理体系CSMS]
    B --> B2[风险评估]
    B --> B3[监控和响应]
    B --> B4[证书管理]
    
    C --> C1[软件更新管理体系SUMS]
    C --> C2[更新风险评估]
    C --> C3[更新验证]
    C --> C4[更新确认]
```

## 质量管理标准

### IATF 16949汽车质量管理
```mermaid
graph TD
    A[IATF 16949标准] --> B[组织环境]
    A --> C[领导作用]
    A --> D[策划]
    A --> E[支持]
    A --> F[运行]
    A --> G[绩效评价]
    A --> H[改进]
    
    F --> F1[运行策划和控制]
    F --> F2[产品和服务要求]
    F --> F3[产品和服务设计开发]
    F --> F4[外部提供过程控制]
    F --> F5[生产和服务提供]
    F --> F6[产品和服务放行]
    F --> F7[不合格输出控制]
```

### VDA质量标准体系
```mermaid
graph LR
    A[VDA标准] --> B[VDA 6.1]
    A --> C[VDA 6.3]
    A --> D[VDA 6.5]
    A --> E[VDA 19]
    
    B --> B1[QM体系审核<br/>德国汽车工业<br/>质量管理要求]
    
    C --> C1[过程审核<br/>制造过程<br/>质量能力评估]
    
    D --> D1[产品审核<br/>最终产品<br/>客户要求符合性]
    
    E --> E1[服务质量评估<br/>售后服务<br/>客户满意度]
```

## 产品开发标准

### ASPICE汽车软件过程改进
```mermaid
graph TD
    A[ASPICE过程模型] --> B[主要生命周期过程]
    A --> C[组织生命周期过程]
    A --> D[支持生命周期过程]
    
    B --> B1[ACQ获取过程]
    B --> B2[SPL供应过程]
    B --> B3[SYS系统工程过程]
    B --> B4[SWE软件工程过程]
    
    C --> C1[MAN管理过程]
    C --> C2[ORG组织过程]
    C --> C3[IMP改进过程]
    C --> C4[REU复用过程]
    
    D --> D1[SUP支持过程]
    D --> D2[配置管理]
    D --> D3[质量保证]
    D --> D4[验证确认]
```

### ASPICE能力等级
```mermaid
graph LR
    A[ASPICE能力等级] --> B[CL0 不完整]
    A --> C[CL1 已执行]
    A --> D[CL2 已管理]
    A --> E[CL3 已确立]
    A --> F[CL4 可预测]
    A --> G[CL5 优化]
    
    B --> B1[过程未实施<br/>或未达到目的]
    
    C --> C1[过程已实施<br/>达到了目的]
    
    D --> D1[过程已管理<br/>产品符合要求]
    
    E --> E1[过程已确立<br/>标准过程]
    
    F --> F1[过程可预测<br/>量化管理]
    
    G --> G1[过程持续优化<br/>创新改进]
```

## 测试认证标准

### Euro NCAP欧洲新车评价
```mermaid
graph TD
    A[Euro NCAP评价] --> B[成人乘员保护]
    A --> C[儿童乘员保护]
    A --> D[弱势道路使用者保护]
    A --> E[安全辅助系统]
    
    E --> E1[速度辅助系统]
    E --> E2[乘员状态监测]
    E --> E3[车道支持系统]
    E --> E4[AEB城市/城际/行人/骑行者]
    E --> E5[安全辅助]
```

### 电磁兼容标准
```mermaid
graph LR
    A[汽车EMC标准] --> B[CISPR 25]
    A --> C[ISO 11452]
    A --> D[ISO 7637]
    A --> E[SAE J1113]
    
    B --> B1[车载设备<br/>无线电骚扰<br/>限值和测试方法]
    
    C --> C1[道路车辆<br/>电气干扰<br/>抗扰度测试]
    
    D --> D1[道路车辆<br/>电气瞬态<br/>传导和耦合]
    
    E --> E1[汽车元件<br/>电磁兼容<br/>测试程序]
```

## 环境与可靠性标准

### 环境测试标准
```mermaid
graph TD
    A[环境测试标准] --> B[温度测试]
    A --> C[湿度测试]
    A --> D[振动测试]
    A --> E[冲击测试]
    A --> F[盐雾测试]
    
    B --> B1[IEC 60068-2-1低温]
    B --> B2[IEC 60068-2-2高温]
    B --> B3[IEC 60068-2-14温变]
    
    C --> C1[IEC 60068-2-3湿热稳态]
    C --> C2[IEC 60068-2-30湿热循环]
    
    D --> D1[IEC 60068-2-6正弦振动]
    D --> D2[IEC 60068-2-64随机振动]
    
    E --> E1[IEC 60068-2-27冲击]
    E --> E2[IEC 60068-2-29碰撞]
    
    F --> F1[IEC 60068-2-52盐雾]
```

### 可靠性标准
```mermaid
graph LR
    A[可靠性标准] --> B[IEC 61709]
    A --> C[IEC 62380]
    A --> D[MIL-HDBK-217]
    A --> E[Telcordia SR-332]
    
    B --> B1[电子元器件<br/>可靠性<br/>参考条件]
    
    C --> C1[电子设备<br/>可靠性数据<br/>手册]
    
    D --> D1[电子设备<br/>可靠性预计<br/>军用标准]
    
    E --> E1[电子设备<br/>可靠性预计<br/>电信标准]
```

## 数据与隐私标准

### 数据保护法规
```mermaid
graph TD
    A[数据保护法规] --> B[GDPR欧盟]
    A --> C[CCPA加州]
    A --> D[中国个保法]
    A --> E[日本个保法]
    
    B --> B1[数据主体权利]
    B --> B2[数据处理原则]
    B --> B3[违规处罚机制]
    
    C --> C1[消费者权利]
    C --> C2[企业义务]
    C --> C3[执法机制]
    
    D --> D1[个人信息权益]
    D --> D2[处理活动规范]
    D --> D3[法律责任]
```

### 车载数据安全
```mermaid
graph LR
    A[车载数据安全] --> B[数据分类分级]
    A --> C[数据处理安全]
    A --> D[数据传输安全]
    A --> E[数据存储安全]
    
    B --> B1[敏感个人信息]
    B --> B2[重要数据]
    B --> B3[一般数据]
    
    C --> C1[最小化原则]
    C --> C2[用途限制]
    C --> C3[同意机制]
    
    D --> D1[加密传输]
    D --> D2[身份认证]
    D --> D3[访问控制]
    
    E --> E1[本地化存储]
    E --> E2[安全备份]
    E --> E3[删除机制]
```
</knowledge>
