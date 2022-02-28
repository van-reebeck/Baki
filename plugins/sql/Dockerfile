FROM fusuf/whatsasena:latest

RUN git clone https://github.com/TSHEPHANG-V/Baki /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/TSHEPHANG-V/Baki

CMD ["node", "bot.js"]
