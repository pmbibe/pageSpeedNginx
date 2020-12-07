# pageSpeedNginx
- Configure  
    ./configure --add-module=/root/incubator-pagespeed-ngx-latest-stable --conf-path=/etc/nginx/nginx.conf --error-log-path=/var/log/nginx/error.log --http-log-path=/var/log/nginx/access.log --with-http_image_filter_module=dynamic --with-http_ssl_module --with-http_v2_module --add-module=../ngx_security_headers --add-module=../headers-more-nginx-module
- How to install  
    https://www.modpagespeed.com/doc/build_ngx_pagespeed_from_source  
- Create nginx.service  
     /usr/lib/systemd/system/nginx.service
