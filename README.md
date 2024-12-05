 # obfuscator-list
* [Abonasera](https://github.com/abonasera/obfuscator) - FOSS. Pretty lightweight because it only encrypts strings. Should not be used on its own, as it wont stop any reverse-engineer.
* [AckerRun](https://github.com/leaks-YCgsasxGZY/AckerObfuscator) - FOSS. Lightweight/Heavy obfuscator depanding on your config. Has some interesting features that not every other obfuscator has. Looks like XenonGuard skid but I can't confirm that.
* [Allatori](http://www.allatori.com/) - Commercial. Was a somewhat popular choice in industry. The v3 has been leaked a long time ago [Allatori-V3](https://github.com/netindev/Allatori-v3.0), tho not nothing special.
* [Ambien](https://github.com/iiiiiiiris/Ambien) - FOSS. Obfuscator that is not getting actively developed anymore. Has some cool packaging features mainly targeting Recaf 2.x with a great succeed since their RedHerring feature adds a fake jar before the real one. Most RE tools don't read backwards like the JVM, so they will read the fake jar. Also has a decent Crasher transformer that confuses various decompilers & other reverse engineering tools. Still contain some bugs/issue to this day.
* [Avaj](https://github.com/cg-dot/avaj) - FOSS. Has a nice way of generating decryption subroutines on string constants. Also has some CFG flattening which is always nice to see.
* [Binscure](https://github.com/4wl/binscure-license-removed) - Commercial. Binscure was a commercial Java obfuscator that had a running spat with Recaf. Its primary advertised features were its crasher and zipping abilities and intense flow/indy obfuscation. However as with most cat-and-mouse games, one side would give up. Since we're using past tense here, its Binscure if you haven't caught on. The ASM/RE tool crashers are now fully patched in Recaf with current versions. The flow and indy obfuscation still is fair for the current market. Can be deobfuscated using [Narumii](https://github.com/narumii/Deobfuscator)/[JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator).
* [Black](https://github.com/CodingGay/BlackObfuscator) - FOSS. Black Obfuscator is an obfuscator for Android APK DexFile, it can help developer to protect source code by control flow flattening, and make it difficult to analyze the actual program control flow.
* [Bozar](https://github.com/vimasig/Bozar) - FOSS. Has some cheap tricks along with GUI that I have seen being used in the Minecraft Community. Definitely a look worth. Can be deobfuscated using [Narumii](https://github.com/narumii/Deobfuscator).
* [BranchLock](https://branchlock.net/) - Commercial. An online, web-based obfuscator primarily known for its AntiDebugging features. It advertises itself as 'modern, lightweight, but powerful,' which is now untrue, considering that it can't compete with modern obfuscators anymore. It appears somewhat in the Minecraft Community. Due to it being web-based, it had some ddos attacks lately, which caused the site to be down.
* [Bruhfuscator](https://github.com/erxson/Bruhfuscator) - FOSS. This obfuscator, based on [Ambien](https://github.com/iiiiiiiris/Ambien), is a skid of multiple FOSS obfuscators, therefore nothing in it is selfmade or special.
* [Caesium](https://github.com/sim0n/Caesium) - FOSS. Has a transformer that implements a well-known HTML injection into any Java reverse-engineering tool that parses HTML tags. Shows alot in Minecraft Community. Can be deobfuscated using [Narumii](https://github.com/narumii/Deobfuscator).
* [CafeVault](https://github.com/Taptzuz/CafeVault) - FOSS. Basic Jar-File Crypter, therefore has a lot of room for improvements. Could be used as lightweight top-layer.
* [CheatBreaker](https://github.com/CheatBreaker/Obf) - FOSS. Decent obfuscation that looks similar to Caesium's, but not as strong. Obfuscation is overall decent. Shows in Minecraft Community. Can be deobfuscated using [JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator).
* [ClassGuard](https://zenofx.com/classguard/) - Commercial. Relies mostly on class encryption with hardcoded AES keys in native libs. Pretty easy IDA/Binary Ninja/Ghidra exercise if you want to flex on your blog on something. Can be deobfuscated using [JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator).
* [ClassCloak](https://github.com/SohamGovande/ClassCloak) - FOSS. Basic obfuscator with string encryption.
* [CodeEncryptor+](https://github.com/4ra1n/code-encryptor-plus) - FOSS. This project uses JNI to encrypt bytecode and JVMTI to decrypt bytecode in order to protect code. It provides two DLL files: one for encryption and one for decryption. During actual execution, only the decryption DLL file is used. It supports custom keys and package names. The encrypted Class files becomes malformed and cannot be parsed. Apart from retaining the Magic part at the beginning, the rest becomes unrecognizable bytes.
* [Colonial](https://github.com/ColonialBuilders/ColonialObfuscator) - FOSS. Rename of [Simple Obfuscator](https://gitlab.com/nickfreeman/SimpleObfuscator), with some additions of [JObf/SB27](https://github.com/superblaubeere27/obfuscator). The string decryption with its hard-coded switch-case slightly reminds of [ZKM (Zelix Klass Master)](https://zelix.com/klassmaster/index.html), tho not nearly as strong.
* [Crater](https://github.com/CraterTeam/Crater) - FOSS. Basic java obfuscator.
* [DashO](https://www.preemptive.com/products/dasho/overview) - Commercial. Shows up a bit in industry and has some interesting ideas (albeit probably outdated) in flow obfuscation. Can be deobfuscated using [JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator).
* [DexGuard](https://www.guardsquare.com/dexguard) - Commercial. Mainly used for obfuscating Android apps. Never saw any samples. Can be deobfuscated using [JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator).
* [dProtect](https://github.com/open-obfuscator/dProtect) - FOSS. dProtect is build on [ProGuard](https://github.com/Guardsquare/proguard) with additional flow-obfuscation, mixed-boolean-arithmetics-transformations and string-encryption. Definitely worth a try.
* 
* [Eskid](https://github.com/PlutoSolutions/EskidRewrite) - Commercial. Decent obfuscator based on [HsGuard](https://github.com/3000IQPlay/HsGuard-Obfuscator) and [Scuti](https://github.com/netindev/scuti/tree/master). Shows alot in Minecraft Community. Could be possibly deobfuscated using [AckeRun's](https://github.com/AckerRun1337) Eskid deobfuscator trasnformer. Got cracked by [PlutoSolution](https://github.com/PlutoSolutions).
* [GOTO](https://github.com/Dimples1337/goto-java-obfuscator) / [GOTO](https://github.com/KgDW/GOTOObfuscator) - FOSS. An obfuscator made by chinese people written in Kotlin. Has interesting features but they are kinda broken.
* [Grunt](https://github.com/SpartanB312/Grunt) - FOSS. Another ofuscator written in Kotlin. Should be used as a lightweight layer of obfuscation. Overall has very based features that are compatible with each other. Mainly known in Minecraft Comunity for it's mixin support renamer and compatibilty with obfuscating Forge mods/Plugins.
* [HsGuard](https://github.com/3000IQPlay/HsGuard-Obfuscator) - FOSS. An obfuscator developed by chinese people. Bad skid of Scuti with minimal additions. Can be deobfuscated using [Narumii](https://github.com/narumii/Deobfuscator).
* [InDy](https://github.com/ventolotl/IndyObfuscator) - FOSS. A simple project that provides an implementation to obfuscate method calls in Java Bytecode by replacing them with invokedynamic instructions.
* J2CC - Private. Flexible quality transpiler with lots of cool features and compatiblity. Nothing else to say.
* [JarObfucator](https://github.com/jar-analyzer/jar-obfuscator) - FOSS. A obfuscator with simple Bytecode transformers such as XOR encryption. Has a Class Encryptor which encrypts the contents of classes and allows you to decrypt them at runtime by using a Java Agent with their decryptor.
* [Javari](https://github.com/3000IQPlay/Javari) - FOSS. A simple obfuscator with a nice GUI and not so nice obfuscation-techniques. 
* [JNIC](https://jnic.dev) - Commercial. One of not so many Java Native Interface Compilers that offers String Encryption, Control Flow with Flattening and their famous Native compiler. This obfuscator is mainly used for the Native compiling and does a really good job doing so. You can see JNIC as an example in RusherHack Loader. Be aware that the Native obfuscation could cause lag or slow down the processes made in the application. If you would decide to use JNIC for obfuscation then make sure to not use it on it's own and instead use something with it. It's what Minecraft uses to obfuscate their vanilla jars but it's alright as long as you have a good config. Also, if your obfuscating a Minecraft client, make sure it's a Forge client because MCP clients using JNIC get cracked sometimes, ex: Myau.
* [JNT]() - Commercial. N/A
* [JBCO](http://www.sable.mcgill.ca/JBCO/) - FOSS. Some interesting flow obfuscation techniques that still work in modern Java. Based on the [Soot](https://github.com/soot-oss/soot) library which is also something worthwhile checking out.
* [JObf/Sb27](https://github.com/superblaubeere27/obfuscator) - FOSS. Pretty outdated. Due to the generic name is more commonly referred to by the author's name superblaubeere27 / sb27. Has some basic features along with a GUI. Still shows allot in the Minecraft Community (Mainly in Japanese/Chinese Anarchy Clients). Can be easily deobfuscated with no effort using [Narumii](https://github.com/narumii/Deobfuscator)/[JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator).
* [JObfuscator](https://www.pelock.com/products/jobfuscator) - Commercial. Most of the obfuscated code are just int/double arrays with some light flow obfuscation (Based off sample). Uses polymorphic algorithm for strings encryption. Has only few features. Last update was made on 09.08.2022 which is a version 1.10.
* [Masxinlingvonta](https://github.com/superblaubeere27/masxinlingvonta) - FOSS. Compiles Java ByteCode to LLVM IR (for obfuscation purposes). 
* [Mosey](https://github.com/Hippo/Mosey) - FOSS. Outdated obfuscator mainly coded in Scala. Overall is no recommended for use since the obfuscation is very light and is easy to deobfuscate. Mainly used for 2+. layer obfuscation. Can be deobfuscated using [Narumii](https://github.com/narumii/Deobfuscator).
* [MyJ2C](https://github.com/MyJ2c/Open-MyJ2c) - FOSS. Obfuscator made by chinese people that managed to skid some of [Allatori's-V3](https://github.com/netindev/Allatori-v3.0) parts such as String Encryption and some other things into their project. Overall only recommend using it when u have nothing else to use. Can be partially deobfuscated using Allatori deobfuscator. Has a interesting feature called "Confusing CallSites".
* [Native/Radioegor146](https://github.com/radioegor146/native-obfuscator) - FOSS. Java .class to .cpp converter for use with JNI.
* [Native+](https://github.com/Araykal/native-obfuscator-plus) - FOSS. Modification of [Native/Radioegor146](https://github.com/radioegor146/native-obfuscator).
* [NeonObf](https://github.com/MoofMonkey/NeonObf) - FOSS. Made up of the easier to defeat obfuscation techniques.  NeonObf is also the name inspiration for Radon.
* [Ob](https://github.com/ShivamMistry/Ob/) - FOSS. Older obfuscator from 2011 with string encryption, branching, and a renamer.
* [Obzcure](https://obzcu.re/) - [Discord](https://discordapp.com/invite/fUCPxq8) (Dead) - Commercial. Web-based obfuscation service with some inspiration taken from Radon and [SkidSuite2](https://github.com/GenericException/SkidSuite/tree/master/archive/skidsuite-2). Used to go by the name "SpigotProtect" so you might see some Spigot plugins using the obfuscation from this product if you
look around hard enough. Can be deobfuscated using [JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator). 
* [ObzucureVM](https://github.com/HoverCatz/ObzcureVirtualMachine) - FOSS. Java Virtual Machine made in Java.
* [Paramorphism](https://paramorphism.dev/) - [Discord](https://discordapp.com/invite/k9DPvEy) (Dead) - Commercial. Was one of the most unusual and unique obfuscators at the time it was an active project in that relied a lot more on the JVM's unusual way of loading JAR archives including zip entries with duplicated names and the [fake directory trick](https://github.com/x4e/fakedirectory). Used to be more commonly used before people started ripping ideas from Paramorphism. Can be deobfuscated using [JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator).
* [Phantom Shield X](https://skidonion.tech/#/) - N/A
* [Popuskator](https://github.com/erxson/Popuskator) - FOSS. Obfuscator based of Ambien. 100% Skidded, nothing custom.
* [qProtect](https://mdma.dev/) - [Discord](https://discord.gg/PrxktvRTt9) - Commercial. Got [cracked](https://crystalpvp.ru/qprotect) millions of times, Devs and Admin only care about money, promotion and like to d0x people that don't like qProtect and possibly harass them or try to scare them. Horrible scam for $70 (Skidfuscator FOSS would do better).
*  [qProtect Lite](https://mdma.dev/) - FCSS. Shittier and free version of [qProtect](https://mdma.dev/). It's complete and utter garbage that includes just limited features of the already garbage obfuscator. Just use the [crack](https://crystalpvp.ru/qprotect) as it will do 10x better, though not good.
* [Radon](https://github.com/ItzSomebody/radon) - FOSS. Abandoned experimental obfuscator by ItsSomebody (The person that made some of the parts of this Obfuscator list). Radon is an open-source free obfuscator. It has a UI that's visually similar to Skidfuscator/ProGuard and it is very intuitive to use. Easy to deobfuscate using [JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator).
* [Reflow](https://github.com/PolyRocketMatt/Reflow) - FOSS. A Java Bytecode Obfuscator.
* [Retype](https://github.com/JTrixEx/Retype) - FOSS. A Java Bytecode Obfuscator.
* [Sandmark](http://sandmark.cs.arizona.edu) - FOSS. Really old obfuscator research project led by Christian Collberg at the University of Arizona. Has some interesting ideas in static and dynamic watermarking (Embeder & Recognizer) are some of the flow obfuscation ideas are good.
* [Scuti](https://github.com/netindev/scuti) - FOSS. Outdated obfuscator. Has an option to pack classes into binary blobs, and load them via a classloader. The binary blob names are just the original class names with simple XOR encryption, and the blob contents are the original class file with simple XOR encryption. Can be deobfuscated using [Narumii](https://github.com/narumii/Deobfuscator).
* [Sentinel](https://cdn.discordapp.com/attachments/972906162641076317/972942077669310556/SentinelObf-1.0-SNAPSHOT-all-obf.jar) - [Discord](https://discord.com/invite/4abh95NzmQ) - FOSS. Dead, Obfuscator mainly known in Minecraft community. Has some basic features. Currently there are no public transformers for it and still can be used. If you decide to use it, make sure to use key "sentinelisback" once you run it in cmd.
* [Skidfuscator Community](https://github.com/skidfuscatordev/skidfuscator-java-obfuscator) - [Discord](https://discord.gg/srFPwUPFX3) - FOSS. Skidfuscator is known obfuscator for its simplicity, ease of use, and effectiveness in protecting Java applications from reverse engineering and tampering. You can get free (community) version having overall strong obfuscation. Paid (Enterprises) version has (Unfinished) Native obfuscation with some other features that aren't included in the Community version. Has its own [documentary website](https://skidfuscator.dev/docs/). Requires libraries (Doesn't have max depth). Free version has slightly broken Matcher. Uses [Maple IR](https://github.com/LLVM-but-worse/maple-ir) framework which is something worth checking out. Shows a lot in Minecraft community. In my opinion this is the best free obfuscator, but layering is needed if you don't know how to config well.
* [Skidfuscator Enterprises](https://skidfuscator.dev/pricing/) - [Discord](https://discord.gg/srFPwUPFX3) - Commercial. Skidfuscator Enterprises is a paid, better version of [Skidfusctor Community](https://github.com/skidfuscatordev/skidfuscator-java-obfuscator), which offers more and better features and in the future will possibly even have Native obfuscation.
* [Souvenir](https://github.com/Body-Alhoha/Souvenir) - FOSS. Lightweight obfuscation that doesn't have anything special. Has only 3 transformers (Light Flow, String, Number).
* [Stringer](https://jfxstore.com/stringer/) - Commercial. Pretty infamous for its complicated AES-based encryption/decryption routines and price. Does not really offer a whole lot of protection, but sometimes does show up in industry. Can be deobfuscated using [JavaDeobfuscator](https://github.com/java-deobfuscator/deobfuscator) and got cracked few times.
* [Virbox Protector](https://lm.virbox.com/product/8.html) - Commercial. A native obfuscator, has a code virtualization made by chinese people It's very different from native obfuscators from github and it's very expensive, almost 10k CNY per year.
* [XenonGuard](https://github.com/darklol9/Some-Java-Obfuscator) - FOSS. XenonGuard is a somewhat decent obfuscator based off CheatBreaker. Kinda looks like free version of ZKM. Has a very good and useful features that not every obfuscator has these days. Even tho there are no public deobfuscation transformers, I still recommend layering it since it's based off CheatBreaker and I am unsure if some transformer are still from CheatBreaker. Overall I really like this one.
* [yGuard](https://www.yworks.com/products/yguard) - FOSS. Functionally equivalent to ProGuard as far as I can tell.
* [zProtect](https://github.com/PotatoSUS/zProtect) - [Discord](https://discord.com/invite/dnGKGuwvGH) - Commercial. Stupid Binscure skid. Not recomended for use. SRC of it has been leaked and their obfuscation could be possibly deobfuscated using [darklols](https://github.com/darklol9) zProtect deobfuscator or using Binscure deobfuscator to semi deobfuscate it.
* [ZKM (Zelix Klass Master)](https://zelix.com/klassmaster/index.html) - Commercial. Zelix KlassMaster Obfuscator is known for its robust obfuscation techniques and strong obfuscation capabilities and is used by many companies to protect their Java applications from reverse engineering and tampering. Currently the best obfuscator for Java right now and always updates their compatiblities for newer or even older Java versions with bug fixes or patches whenever there are public deobfuscation transformers. The only thing is, is with a bad config and no layering you'll end up like [Opal Client](https://opal.wtf/) getting cracked every update..
* Zortfuscator - Commercial. Dead, not so known obfuscator. Can tell that it has good obfuscation techniques from the look at the samples they have on their discord server and some small sample in a video made by [akita](https://www.youtube.com/watch?v=0B9SPdt75JQ).

# Obfuscation Branchmarks:
**https://github.com/huzpsb/JavaObfuscatorTest**
