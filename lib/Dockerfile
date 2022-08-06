FROM fusuf/whatsasena:latest

RUN git clone https://https://github.com/sharry-martin/zimbot-v4 /Drips/Zimbotv4

WORKDIR /Drips/Zimbotv4

ENV TZ=Africa/Kenya

RUN npm install

RUN npm install supervisor -g
RUN yarn install --ignore-engines
CMD ["node", "index.js"]
