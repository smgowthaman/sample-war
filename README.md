# .bash_profile
# Get the aliases and functions
#
if [ -f ~/.bashrc ]; then
        ~/.bashrc
fi

# User specific environment and startup programs

PATH=$PATH:$HOME/bin

JAVA_HOME=/usr/lib/jvm/java-21-openjdk-amd64
PATH=$PATH:$HOME/bin:$JAVA_HOME


M2_HOME=/opt/apache-maven-3.9.9
M2=/opt/apache-maven-3.9.9/bin

PATH=$PATH:$HOME/bin:$JAVA_HOME:$M2:$M2_HOME

export PATH







	<plugin>
           <groupId>org.apache.maven.plugins</groupId>
           <artifactId>maven-war-plugin</artifactId>
           <version>3.4.0</version>
        </plugin>




