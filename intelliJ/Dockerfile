FROM java:8

ENV HOME /home/user
RUN useradd --create-home --home-dir $HOME user \
    && chown -R user:user $HOME
USER user

RUN mkdir $HOME/java

ADD ideaIC-14.1.4.tar.gz $HOME


CMD ["/home/user/idea-IC-141.1532.4/bin/idea.sh"]
