# maven-repo
maven仓库

## 使用方式
```bash 
# pom文件中添加对应仓库
<repositories>
    <repository>
        <id>maven-repo-master</id>
        <url>https://raw.github.com/zhouzhipeng/maven-repo/master/</url>
        <snapshots>
            <enabled>true</enabled>
            <updatePolicy>always</updatePolicy>
        </snapshots>
    </repository>
</repositories>

```
