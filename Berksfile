source 'https://supermarket.getchef.com'

# core cookbooks
cookbook 'apache2', git: "https://github.com/peterabbott/apache2-cookbook.git", branch: "bugfix/service-start"
cookbook 'java'
cookbook 'mongodb'

# bug with tomcat cookbook 
cookbook 'tomcat', git: 'https://github.com/peterabbott/tomcat.git', branch: 'bugfix/centos-tomcat7'
#cookbook 'tomcat'

# environment variations
cookbook 'apt'
cookbook 'yum'
