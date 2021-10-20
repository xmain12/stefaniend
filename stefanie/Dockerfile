FROM fusuf/whatsasena:latest

RUN git clone https://github.com/xmain12/stefaniend /root/ales
WORKDIR /root/ales/
RUN git clone https://github.com/Kaweebro/Config
RUN git clone https://github.com/xmain12/Angela-x
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]