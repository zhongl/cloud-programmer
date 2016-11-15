# cloud-programmer

## 安装 Vagrant 插件

```shell
vagrant plugin install vagrant-vbguest vagrant-docker-compose       
```

> 安装过程中 vagrant 默认会去<https://gems.hashicorp.com>找， 但大多插件都是发布在<https://rubygems.org>上的，通过下面的 Options 也许能帮你节省一些时间。
>
> `--plugin-source https://rubygems.org --plugin-clean-sources` 

### 其它有用的插件

- [vagrant-proxyconf](https://github.com/tmatilai/vagrant-proxyconf) 
- [vagrant-cachier](https://github.com/fgrehm/vagrant-cachier)