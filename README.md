sudo cat /etc/profile.d/java.sh
********
export JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64
export PATH=$JAVA_HOME/bin:$PATH

sudo cat /etc/profile.d/ant.sh
*******************************************
export ANT_HOME=/usr/local/apache-ant-1.9.7/
export PATH=$ANT_HOME/bin:$PATH

cat /etc/profile.d/m3.sh
*******************************************
export M3_HOME=/usr/local/apache-maven-3.3.9/
export PATH=$M3_HOME/bin:$PATH
