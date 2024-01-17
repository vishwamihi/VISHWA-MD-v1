FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/vishwamihi/VISHWA-MD /root/vishwa-md
WORKDIR /root/vishwa-md/
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
