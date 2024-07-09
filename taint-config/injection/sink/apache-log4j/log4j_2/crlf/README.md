- **概述**：
  Apache Log4j 是一个用于 Java 应用程序的日志记录库，本目录下的API提供了多种方法来记录不同级别的日志信息，包括调试、信息、警告、错误和致命错误。
- **常见使用场景**
    这些API通常用于输出各种日志如记录错误和异常，记录运行时信息，进行警告等，还可以和日志审计系统进行配合
- **安全风险**
    CRLF注入：攻击者可以通过构造恶意输入CRLF回车换行，伪造日志信息，误导监测人员乃至影响审计系统，也可以通过输入大量报错或无关信息毁坏日志