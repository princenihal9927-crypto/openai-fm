एक छोटे से गाँव में एक गरीब बूढ़ी माँ रहती थी। उसका कोई नहीं था। वह अकेले एक झोपड़ी में रहती और दूसरों के घर काम करके अपना गुज़ारा करती थी।
उसी गाँव में एक आवारा कुत्ता भी रहता था। लोग उसे पत्थर मारते, भगा देते, कोई उसे खाना नहीं देता था। एक दिन ठंड और भूख से काँपता हुआ कुत्ता बूढ़ी माँ की झोपड़ी के पास आकर बैठ गया।
बूढ़ी माँ ने उसे देखा और दया आ गई।
उसने अपने हिस्से की थोड़ी-सी रोटी कुत्ते को दे दी और बोली,
“बेटा, मेरे पास ज़्यादा नहीं है, पर जो है वही खा लो।”
कुत्ता बहुत खुश हुआ। उस दिन से वह बूढ़ी माँ के साथ रहने लगा। वह रोज़ उसके घर की रखवाली करता, रात को झोपड़ी के बाहर सोता और किसी अजनबी को पास नहीं आने देता।
एक रात कुछ चोर गाँव में आए। जब वे बूढ़ी माँ की झोपड़ी के पास पहुँचे, तो कुत्ता ज़ोर-ज़ोर से भौंकने लगा और चोरों पर झपट पड़ा। उसकी आवाज़ सुनकर गाँव वाले जाग गए और चोर भाग गए।
अगले दिन पूरे गाँव ने कुत्ते की बहादुरी की तारीफ की। अब लोग उसे खाना देने लगे और बूढ़ी माँ का भी सम्मान करने लगे।
बूढ़ी माँ बोली,
“जिसे सब बेकार समझते हैं, वही कभी-कभी सबसे बड़ा सहारा बनता है।”

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
![NextJS](https://img.shields.io/badge/Built_with-NextJS-blue)
![OpenAI API](https://img.shields.io/badge/Powered_by-OpenAI_API-orange)

[OpenAI.fm](https://openai.fm) is an interactive demo to showcase the new OpenAI text-to-speech models.
It is built with NextJS and the [Speech API](https://platform.openai.com/docs/api-reference/audio/createSpeech).

For more information about text-to-speech using the OpenAI API, check out our [documentation](https://platform.openai.com/docs/guides/text-to-speech).

![screenshot](./public/screenshot.jpg)

## How to run

1. **Set up the OpenAI API:**

   - If you're new to the OpenAI API, [sign up for an account](https://platform.openai.com/signup).
   - Follow the [Quickstart](https://platform.openai.com/docs/quickstart) to retrieve your API key.

2. **Clone the Repository:**

   ```bash
   git clone https://github.com/openai/openai-fm.git
   ```

3. **Set the OpenAI API key:**

   2 options:

   - Set the `OPENAI_API_KEY` environment variable [globally in your system](https://platform.openai.com/docs/libraries#create-and-export-an-api-key)
   - Set the `OPENAI_API_KEY` environment variable in the project: Create a `.env` file at the root of the project and add the following line (see `.env.example` for reference):

   ```bash
   OPENAI_API_KEY=<your_api_key>
   ```

4. **Install dependencies:**

   Run in the project root:

   ```bash
   npm install
   ```

5. **(Optional) Connect to a hosted database:**

   If you want to use the sharing feature, you need to connect to a hosted postgres database.
   You should set the environment variables in a `.env` file at the root of the project to connect to your database as shown in `.env.example`.

   ```bash
   POSTGRES_URL="postgresql://username:password@host:port/database_name"
   ```

   This step is not needed to run the application and only affects the sharing feature.

6. **Run the app:**

   ```bash
   npm run dev
   ```

   The app will be available at [`http://localhost:3000`](http://localhost:3000).

> [!NOTE]  
> Be aware that if you deploy this app to a public server, you are responsible for any usage it may incur using your OpenAI API key.

## Contributors

### OpenAI team

- [Tyler Smith](https://github.com/tylersmith-openai)
- [Karolis Kosas](https://github.com/karoliskosas)
- [Justin Jay Wang](https://github.com/justinjaywang)
- [Bobby Stocker](https://github.com/stocker-openai)
- [Jeff Harris](https://github.com/jeffsharris)
- [Romain Huet](https://github.com/romainhuet)
- [David Weedon](https://github.com/weedon-openai)
- [Iaroslav Tverdokhlib](https://github.com/itv-openai)
- [Adam Walker](https://github.com/awalker-openai)
- [Edwin Arbus](https://x.com/edwinarbus)
- [Katia Gil Guzman](https://github.com/katia-openai)

### Contributing

You are welcome to open issues or submit PRs to improve this app, however, please note that we may not review all suggestions.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
