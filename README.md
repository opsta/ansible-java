# Ansible Role: Java



## Requirements

None.

## Java version
- You can change Java version in defaults/main.yml and select Java version in below table.

---
| Java Version  | apt package    | yum package        | remark         |
| :-            | :-             | :-                 | :-----         |
| 8             | openjdk-8-jdk  | java-1.8.0-openjdk | Default values |
| 11            | openjdk-11-jdk | java-11-openjdk    | -              |
| 13            | openjdk-13-jdk | -                  | -              |
| 16            | openjdk-16-jdk | -                  | -              |
| 17            | openjdk-17-jdk | java-17-openjdk    | -              |




## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - ansible-java


## License

MIT

## Author Information

Opsta (Thailand) Co.,Ltd.
