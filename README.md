# JDK with Ansible

Start of a template for installing and configuring a JDK.

## Parameters

 * `jdk_version` - Version of JDK
 * `jdk_download_url` - URL of tar.gz for release
 * `jdk_download_sha256` - Checksum of tar.gz for release

## Testing

Credit: Tested with vagrant image from [@geerlingguy's Ansible for Devops](https://github.com/geerlingguy/ansible-for-devops)

### Initial Install
```
vagrant up
```

### Reapply provisioning
```
vagrant provision
```