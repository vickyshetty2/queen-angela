FROM fusuf/whatsasena:latest

RUN git clone https://github.com/zim-bot/queen-angela /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Africa/Harare
RUN npm install supervisor -g
RUN yarn install --network-concurrency 1

CMD ["node", "bot.js"]
