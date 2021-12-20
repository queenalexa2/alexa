FROM blackamda/queenamdi:public

RUN git clone https://github.com/queenalexa2/alexa /root/alexa
WORKDIR /root/alexa/
ENV TZ=Asia/Colombo
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "assets/module.js"]
