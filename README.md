# Software security paper list


This repository contains a curated list of papers relevant to
* software security
* program analysis
* systems security

The list is divided into further sub-topics and we include a section called "General" which contains papers that either have not been sorted into a sub-topic yet or do not fit into any sub-topics.


This list is maintained by [David Korczynski](https://twitter.com/Davkorcz). PRs are very welcomed.

## Download all automatically
The `auto_download.py` script can be used to download either all of the papers or the papers for a given subtopic.

`auto_download.py` will create a directory `out` in the current working directory if its not already existing. Then it will create another folder in `out` with the name of the sub-topic you are choosing to download or `All` in case you download all papers.

Example uses:
```
# Download all papers
python ./auto_download.py All

# Download all papers related to Fuzzing
python ./auto_download.py Fuzzing

# Download all papers related to Malware
python ./auto_download.py Malware
```

# Papers

## General

- [A Framework for File Format Fuzzing with Genetic Algorithms](https://trace.tennessee.edu/cgi/viewcontent.cgi?article=2402&context=utk_graddiss)
- [Differential Testing for Software](https://www.hpl.hp.com/hpjournal/dtj/vol10num1/vol10num1art9.pdf)
- [Effective Random Testing of Concurrent Programs](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.73.876&rep=rep1&type=pdf)
- [A Randomized Dynamic Program Analysis Technique for Detecting Real Deadlocks](https://www.cis.upenn.edu/~mhnaik/papers/pldi09b.pdf)
- [Tupni: Automatic Reverse Engineering of Input Formats](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/tupni-ccs08.pdf)
- [Randomized Active Atomicity Violation Detection in Concurrent Programs](https://parlab.eecs.berkeley.edu/sites/all/parlab/files/Randomized%20Active%20Atomicity%20Violation%20Detection%20in%20Concurrent%20Programs.pdf)
- [Privacy Oracle: a System for Finding Application Leaks with Black Box Differential Testing](https://homes.cs.washington.edu/~yoshi/papers/PrivacyOracle/privacyoracle-ccs2008.pdf)
- [PEBIL: Efficient Static Binary Instrumentation for Linux](http://users.sdsc.edu/~lcarring/Papers/2010_ISPASS.pdf)
- [TypeSan: Practical Type Confusion Detection](https://nebelwelt.net/publications/files/16CCS2.pdf)
- [HexType: Efficient Detection of Type Confusion Errors for C++](https://nebelwelt.net/files/17CCS.pdf)
- [T-Fuzz: fuzzing by program transformation](https://nebelwelt.net/files/18Oakland.pdf)
- [Skyfire: Data-Driven Seed Generation for Fuzzing](https://www.ieee-security.org/TC/SP2017/papers/42.pdf)
- [Dynamic Test Generation To Find Integer Bugs in x86 Binary Linux
Programs](https://people.eecs.berkeley.edu/~daw/papers/smartfuzz-use09.pdf)
- [Fuzzing: The State of the Art](https://fuzzinginfo.files.wordpress.com/2012/05/dsto-tn-1043-pr.pdf)
- [Vulcan Binary transformation in a distributed environment](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/tr-2001-50.pdf)
- [Automated Detection, Exploitation, and Elimination of Double-Fetch Bugs using Modern CPU Features](https://arxiv.org/pdf/1711.01254.pdf)
- [Angora: Efficient Fuzzing by Principled Search](https://web.cs.ucdavis.edu/~hchen/paper/chen2018angora.pdf)
- [Android Permissions Demystified](https://people.eecs.berkeley.edu/~dawnsong/papers/2011%20Android%20permissions%20demystified.pdf)
- [Well There’s Your Problem: Isolating the Crash-Inducing Bits in a Fuzzed File](https://resources.sei.cmu.edu/asset_files/TechnicalNote/2012_004_001_28149.pdf)
- [Path-Exploration Lifting: Hi-Fi Tests for Lo-Fi Emulators](https://people.eecs.berkeley.edu/~dawnsong/papers/2012%20Path%20Exploration%20Lifting%20Hi%20Fi%20Tests%20for%20Lo%20Fi%20Emulators.pdf)
- [perf fuzzer: Targeted Fuzzing of the perf event open() System Call](http://web.eece.maine.edu/~vweaver/projects/perf_events/fuzzer/2015_perf_fuzzer_tr.pdf)
- [PULSAR: Stateful Black-Box Fuzzing of Proprietary Network Protocols](https://hugogascon.com/publications/2015-securecomm.pdf)
- [Driller: Augmenting Fuzzing Through Selective Symbolic Execution](https://sites.cs.ucsb.edu/~vigna/publications/2016_NDSS_Driller.pdf)
- [ThreadSanitizer – data race detection in practice](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/35604.pdf)
- [Enforcing Forward-Edge Control-Flow Integrity in GCC & LLVM](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/42808.pdf)
- [MemorySanitizer: fast detector of uninitialized memory use in C++](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/43308.pdf)
- [Random Testing for Security: Blackbox vs. Whitebox Fuzzing](https://patricegodefroid.github.io/public_psfiles/abstract-rt2007.pdf)
- [Learn&Fuzz: Machine Learning for Input Fuzzing](https://arxiv.org/pdf/1701.07232.pdf)
- [Model-Based Whitebox Fuzzing for Program Binaries](https://mboehme.github.io/paper/ASE16.pdf)
- [AddressSanitizer: A Fast Address Sanity Checker](https://www.usenix.org/system/files/conference/atc12/atc12-final39.pdf)
- [CAB-Fuzz: Practical Concolic Testing Techniques for COTS Operating Systems](https://www.usenix.org/system/files/conference/atc17/atc17-kim.pdf)
- [Robust Signatures for Kernel Data Structures](https://www.cc.gatech.edu/~brendan/ccs09_siggen.pdf)
- [Scheduling Black-box Mutational Fuzzing](https://users.ece.cmu.edu/~sangkilc/papers/ccs13-woo.pdf)
- [Hawkeye: Towards a Desired Directed Grey-box Fuzzer](https://chenbihuan.github.io/paper/ccs18-chen-hawkeye.pdf)
- [Chopped Symbolic Execution](https://srg.doc.ic.ac.uk/files/papers/chopper-icse-18.pdf)
- [Automated Test Input Generation for Android: Are We There Yet?](https://arxiv.org/pdf/1503.07217.pdf)
- [Cryptographic Function Detection in Obfuscated Binaries via Bit-precise Symbolic Loop Mapping](https://faculty.ist.psu.edu/wu/papers/CryptoHunt.pdf)
- [RETracer: Triaging Crashes by Reverse Execution from Partial Memory Dumps](https://softsec.kaist.ac.kr/~sangkilc/papers/cui-icse16.pdf)
- [DELTA: A Security Assessment Framework for Software-Defined Networks](https://pdfs.semanticscholar.org/ad1d/64e9e431681a088db680adcf1cb479fc22fc.pdf)
- [Simplifying and Isolating Failure-Inducing Input](https://www.cs.purdue.edu/homes/xyzhang/fall07/Papers/delta-debugging.pdf)
- [Designing New Operating Primitives to Improve Fuzzing Performance](https://multics69.github.io/pages/pubs/fuzzing-xu-ccs17.pdf)
- [Send Hardest Problems My Way: Probabilistic Path Prioritization for Hybrid Fuzzing](https://www.cs.ucr.edu/~heng/pubs/digfuzz_ndss19.pdf)
- [Dowsing for Overflows: A Guided Fuzzer to Find Buffer Boundary Violations](https://www.cs.vu.nl/~herbertb/papers/dowser_usenixsec13.pdf)
- [Fitness-Guided Path Exploration in Dynamic Symbolic Execution](https://www.microsoft.com/en-us/research/wp-content/uploads/2009/06/dsn09-fitnex1.pdf)
- [Enforceable Security Policies](https://www.cs.cornell.edu/fbs/publications/EnfSecPols.pdf)
- [Enemy of the State: A State-Aware Black-Box Web Vulnerability Scanner](https://www.usenix.org/system/files/conference/usenixsecurity12/sec12-final225.pdf)
- [FairFuzz: A Targeted Mutation Strategy for Increasing Greybox Fuzz Testing Coverage](https://www.carolemieux.com/fairfuzz-ase18.pdf)
- [LZfuzz: a fast compression-based fuzzer for poorly documented protocols](https://digitalcommons.dartmouth.edu/cgi/viewcontent.cgi?article=1318&context=cs_tr)
- [Feedback-directed Random Test Generation](https://homes.cs.washington.edu/~mernst/pubs/feedback-testgen-icse2007.pdf)
- [Probability-Based Parameter Selection for Black-Box Fuzz Testing](http://webblaze.cs.berkeley.edu/papers/FLAX.pdf)
- [FLAX: Systematic Discovery of Client-side Validation Vulnerabilities in Rich Web Applications]()
- [Singularity: Pattern Fuzzing for Worst Case Complexity](https://www.cs.utexas.edu/users/isil/fse18.pdf)
- [Representation Dependence Testing using Program Inversion](https://core.ac.uk/download/pdf/207770249.pdf)
- [Deriving Input Syntactic Structure From Execution](https://www.cs.purdue.edu/homes/xyzhang/Comp/fse08.pdf)
- [Turning Programs against Each Other: High Coverage Fuzz-Testing using Binary-Code Mutation and Dynamic Slicing](https://www.ida.liu.se/~ulfka17/papers/FSE2015.pdf)
- [SoftBound: Highly Compatible and Complete Spatial Memory Safety for C](https://www.cs.rutgers.edu/~santosh.nagarakatte/papers/pldi09_softbound.pdf)
- [An Empirical Study of the Reliability of UNIX Utilities](ftp://ftp.cs.wisc.edu/paradyn/technical_papers/fuzz.pdf)
- [Evaluating Fuzz Testing](https://arxiv.org/pdf/1808.09700.pdf)
- [Enhancing Memory Error Detection for Large-Scale Applications and Fuzz Testing](http://cps.kaist.ac.kr/papers/18-MEDS-han.pdf)
- [CodeAlchemist: Semantics-Aware Code Generation to Find Vulnerabilities in JavaScript Engines](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_05A-5_Han_paper.pdf)
- [Hulk: Eliciting Malicious Behavior in Browser Extensions](https://www.usenix.org/system/files/conference/usenixsecurity14/sec14-paper-kapravelos.pdf)
- [Taint-based Directed Whitebox Fuzzing](https://people.csail.mit.edu/rinard/paper/icse09.pdf)
- [Detecting Atomic-Set Serializability Violations in Multithreaded Programs through Active Randomized Testing](https://www.cs.cityu.edu.hk/~wkchan/papers/icse10-lai+cheung+chan.pdf)
- [Billions and Billions of Constraints: Whitebox Fuzz Testing in Production](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/main-may10.pdf)
- [Making Malory Behave Maliciously: Targeted Fuzzing of Android Execution Environments](https://www.software-lab.org/publications/icse2017-fuzzdroid.pdf)
- [IFuzzer: An Evolutionary Interpreter Fuzzer using Genetic Programming](https://download.vusec.net/papers/ifuzzer-esorics16.pdf)
- [IntelliDroid: A Targeted Input Generator for the Dynamic Analysis of Android Malware](https://security.csl.toronto.edu/papers/mwong_ndss2016.pdf)
- [CETS: Compiler-Enforced Temporal Safety for C](https://www.cs.rutgers.edu/~santosh.nagarakatte/papers/ismm10-cets.pdf)
- [jFuzz: A Concolic Whitebox Fuzzer for Java](https://ece.uwaterloo.ca/~vganesh/Publications_files/vg-NFM2009-jFuzz.pdf)
- [T-Fuzz: Model-Based Fuzzing for Robustness Testing of Telecommunication Protocols](https://core.ac.uk/download/pdf/187598761.pdf)
- [KiF: A stateful SIP Fuzzer](https://hal.inria.fr/inria-00166947/PDF/Kif_A_stateful_SIP_Fuzzer.pdf)
- [Symbolic Execution and Program Testing](https://www.cs.umd.edu/class/fall2014/cmsc631/papers/king-symbolic-execution.pdf)
- [GRT: Program-Analysis-Guided Random Testing](https://people.kth.se/~artho/papers/lei-ase2015.pdf)
- [Pin: Building Customized Program Analysis Tools with Dynamic Instrumentation](https://www.cs.ucr.edu/~heng/teaching/cs260-winter2017/luk05pin.pdf)
- [Automated Testing for SQL Injection Vulnerabilities: An Input Mutation Approach](https://www.researchgate.net/profile/Cu_Nguyen/publication/262048518_Automated_Testing_for_SQL_Injection_Vulnerabilities_An_Input_Mutation_Approach/links/00b495367f13ad00a5000000/Automated-Testing-for-SQL-Injection-Vulnerabilities-An-Input-Mutation-Approach.pdf)
- [MoonShine: Optimizing OS Fuzzer Seed Selection with Trace Distillation](https://www.cs.columbia.edu/~suman/docs/moonshine.pdf)
- [Automated Whitebox Fuzz Testing](https://patricegodefroid.github.io/public_psfiles/ndss2008.pdf)
- [PeriScope: An Effective Probing and Fuzzing Framework for the Hardware-OS Boundary](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_04A-1_Song_paper.pdf)
- [Dynamic Taint Analysis for Automatic Detection, Analysis, and Signature Generation of Exploits on Commodity Software](http://bitblaze.cs.berkeley.edu/papers/taintcheck-full.pdf)
- [NEZHA: Efficient Domain-Independent Differential Testing](https://www.cs.columbia.edu/~suman/docs/nezha.pdf)
- [Prospex: Protocol Specification Extraction](https://sites.cs.ucsb.edu/~chris/research/doc/oakland09_prospex.pdf)
- [CollAFL: Path Sensitive Fuzzing](http://barbie.uta.edu/~xlren/Fuzzing/path-sensitive-fuzzing.pdf)
- [All You Ever Wanted to Know About Dynamic Taint Analysis and Forward Symbolic Execution (but might have been afraid to ask)](https://users.ece.cmu.edu/~aavgerin/papers/Oakland10.pdf)
- [KameleonFuzz: Evolutionary Fuzzing for Black-Box XSS Detection](https://www.cs.huji.ac.il/~ai/projects/2014/EvolutionaryXSSDetector/files/original_article.pdf)
- [Understanding Integer Overflow in C/C++](https://www.cs.utah.edu/~regehr/papers/overflow12.pdf)
- [DART: Directed Automated Random Testing](https://web.eecs.umich.edu/~weimerw/2014-6610/reading/p213-godefroid.pdf)
- [DIFUZE: Interface Aware Fuzzing for Kernel Drivers](https://acmccs.github.io/papers/p2123-corinaA.pdf)
- [Directed Greybox Fuzzing](https://acmccs.github.io/papers/p2329-bohmeAemb.pdf)
- [IMF: Inferred Model-based Fuzzer](https://acmccs.github.io/papers/p2345-hanA.pdf)
- [Many-Core Compiler Fuzzing](http://multicore.doc.ic.ac.uk/tools/CLsmith/PLDI15/paper.pdf)
- [PerfFuzz: Automatically Generating Pathological Inputs](https://www.carolemieux.com/perffuzz-issta2018.pdf)
- [Pex–White Box Test Generation for .NET](https://web.eecs.umich.edu/~weimerw/2014-6610/reading/pex.pdf)
- [Taming Compiler Fuzzers](http://web.engr.oregonstate.edu/~wongwe/papers/pdf/pldi13.pdf)
- [Synthesizing Racy Tests](https://www.cs.purdue.edu/homes/suresh/papers/pldi15a.pdf)
- [Coverage-Directed Differential Testing of JVM Implementations](https://chengniansun.bitbucket.io/papers/pldi16.pdf)
- [Synthesizing Program Input Grammars](https://arxiv.org/pdf/1608.01723.pdf)
- [Grammar-based Whitebox Fuzzing](https://people.csail.mit.edu/akiezun/pldi-kiezun.pdf)
- [Polyglot: Automatic Extraction of Protocol Message Format using Dynamic Binary Analysis](http://bitblaze.cs.berkeley.edu/papers/polyglot_ccs07_av.pdf)
- [PScout: Analyzing the Android Permission Specification](https://security.csl.toronto.edu/papers/PScout-CCS2012-web.pdf)
- [QuickFuzz: An Automatic Random Fuzzer for Common File Formats](https://people.kth.se/~buiras/publications/QFHaskell2016.pdf)
- [QTEP: Quality-Aware Test Case Prioritization](http://asset.uwaterloo.ca/qtep/qtep.pdf)
- [Race Directed Random Testing of Concurrent Programs](https://www.cs.columbia.edu/~junfeng/09fa-e6998/papers/racefuzz.pdf)
- [Input Generation via Decomposition and Re-Stitching: Finding Bugs in Malware](http://bitblaze.cs.berkeley.edu/papers/restitching.pdf)
- [S2E: A Platform for In-Vivo Multi-Path Analysis of Software Systems](https://cseweb.ucsd.edu/~dstefan/cse291-fall16/papers/s2e.pdf)
- [Fuzzing with Code Fragments](https://www.usenix.org/system/files/conference/usenixsecurity12/sec12-final73.pdf)
- [Optimizing Seed Selection for Fuzzing](https://www.usenix.org/system/files/conference/usenixsecurity14/sec14-paper-rebert.pdf)
- [Protocol State Fuzzing of TLS Implementations](https://www.usenix.org/system/files/conference/usenixsecurity15/sec15-paper-de-ruiter.pdf)
- [Type Casting Verification: Stopping an Emerging Attack Vector](https://www.usenix.org/system/files/conference/usenixsecurity15/sec15-paper-lee.pdf)
- [Digtool: A Virtualization-Based Framework for Detecting Kernel Vulnerabilities](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-pan.pdf)
- [kAFL: Hardware-Assisted Feedback Fuzzing for OS Kernels](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-schumilo.pdf)
- [Qsym : A Practical Concolic Execution Engine Tailored for Hybrid Fuzzing](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-yun.pdf)
- [CUTE: A Concolic Unit Testing Engine for C](http://mir.cs.illinois.edu/marinov/publications/SenETAL05CUTE.pdf)
- [Abusing File Processing in Malware Detectors for Fun and Profit](https://www.cs.cornell.edu/~shmat/shmat_oak12av.pdf)
- [Steelix: program-state based binary fuzzing](https://people.engr.tamu.edu/guofei/paper/Wang_TISSEC11_TaintScope.pdf)
- [Checksum-Aware Fuzzing Combined with Dynamic Taint Analysis and Symbolic Execution]()
- [Statically-Directed Dynamic Automated Test Generation](https://www.domagoj-babic.com/uploads/Pubs/ISSTA11sandwich/issta11sandwich.pdf)
- [Systematic Fuzzing and Testing of TLS Libraries](https://www.nds.ruhr-uni-bochum.de/media/nds/veroeffentlichungen/2016/10/19/tls-attacker-ccs16.pdf)
- [STADS: Software Testing as Species Discovery](https://arxiv.org/pdf/1803.02130.pdf)
- [Valgrind: A Framework for Heavyweight Dynamic Binary Instrumentation](https://www.cs.columbia.edu/~junfeng/09fa-e6998/papers/valgrind.pdf)
- [A Platform for Secure Static Binary Instrumentation](http://seclab.cs.sunysb.edu/seclab/pubs/vee14.pdf)
- [Enhancing Symbolic Execution with Veritesting](https://users.ece.cmu.edu/~aavgerin/papers/veritesting-icse-2014.pdf)
- [Autodafe: an Act of Software Torture](https://infoscience.epfl.ch/record/140525/files/Vuagnoux05.pdf)
- [VUzzer: Application-aware Evolutionary Fuzzing](https://download.vusec.net/papers/vuzzer_ndss17.pdf)
- [Towards Optimization-Safe Systems: Analyzing the Impact of Undefined Behavior](https://people.csail.mit.edu/nickolai/papers/wang-stack.pdf)
- [Disco: Running commodity operating systems on scalable multiprocessors](http://www.cs.cornell.edu/courses/cs6411/2018sp/papers/bugnion97disco.pdf)
- [Jump-Oriented Programming: A New Class of Code-Reuse Attack](https://people.engr.ncsu.edu/tkbletsc/pubs/JOP.pdf)
- [Can DREs Provide Long-Lasting Security? The Case of Return-Oriented Programming and the AVC Advantage](https://www.usenix.org/legacy/events/evtwote09/tech/full_papers/checkoway.pdf)
- [Klee: Unassisted and automatic generation of high-coverage tests for complex systems programs](https://hci.stanford.edu/cstr/reports/2008-03.pdf)
- [Exe: automatically generating inputs of death](https://web.stanford.edu/~engler/exe-ccs-06.pdf)
- [The s2e platform: Design, implementation, and applications](https://dslab.epfl.ch/pubs/s2e-tocs.pdf)
- [Decoupling dynamic program analysis from execution in virtual environments](https://www.usenix.org/legacy/event/usenix08/tech/full_papers/chow/chow.pdf)
- [Understanding data lifetime via whole system simulation.](https://benpfaff.org/papers/taint.pdf)
- [Mining specifications of malicious behavior](https://publik.tuwien.ac.at/files/pub-inf_5316.pdf)
- [Decompilation of binary programs.](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.14.8073&rep=rep1&type=pdf)
- [Minos: Control Data Attack Prevention Orthogonal to Memory Model](http://people.cs.uchicago.edu/~ftchong/papers/micro2004.pdf)
- [Tainting is Not Pointless](https://web.stanford.edu/group/mast/cgi-bin/drupal/system/files/2010.taintingpoint.osr_.pdf)
- [Stitching the Gadgets: On the Ineffectiveness of Coarse-Grained Control-Flow Integrity Protection](https://www.usenix.org/system/files/conference/usenixsecurity14/sec14-paper-davi.pdf)
- [Size Does Matter: Why Using Gadget-Chain Length to Prevent Code-Reuse Attacks is Hard](http://www.syssec-project.eu/m/page-media/3/sec14-paper-goktas.pdf)
- [ROPMEMU: A Framework for the Analysis of Complex Code-Reuse Attacks](http://www.s3.eurecom.fr/docs/asiaccs16_graziano.pdf)





## Virtualisation
- [Xen and the Art of Virtualization](https://www.cl.cam.ac.uk/research/srg/netos/papers/2003-xensosp.pdf)
- [QEMU, a Fast and Portable Dynamic Translator](https://www.usenix.org/legacy/publications/library/proceedings/usenix05/tech/freenix/full_papers/bellard/bellard.pdf)


## Fuzzing
- [HFL: Hybrid Fuzzing on the Linux Kernel, 2020](https://www.unexploitable.systems/publication/kimhfl/)
- [HotFuzz: Discovering Algorithmic Denial-of-Service Vulnerabilities Through Guided Micro-Fuzzing, 2020](https://www.researchgate.net/publication/339164746_HotFuzz_Discovering_Algorithmic_Denial-of-Service_Vulnerabilities_Through_Guided_Micro-Fuzzing)
- [HYPER-CUBE: High-Dimensional Hypervisor Fuzzing, 2020](https://www.syssec.ruhr-uni-bochum.de/media/emma/veroeffentlichungen/2020/02/07/Hyper-Cube-NDSS20.pdf)
- [Not All Coverage Measurements Are Equal: Fuzzing by Coverage Accounting for Input Prioritization, 2020](https://www.ndss-symposium.org/wp-content/uploads/2020/02/24422.pdf)
- [CodeAlchemist: Semantics-Aware Code Generation to Find Vulnerabilities in JavaScript Engines, 2019](https://daramg.gift/paper/han-ndss2019.pdf)
- [PeriScope: An Effective Probing and Fuzzing Framework for the Hardware-OS Boundary, 2019](https://people.cs.kuleuven.be/~stijn.volckaert/papers/2019_NDSS_PeriScope.pdf)
- [REDQUEEN: Fuzzing with Input-to-State Correspondence, 2019](https://www.syssec.ruhr-uni-bochum.de/media/emma/veroeffentlichungen/2018/12/17/NDSS19-Redqueen.pdf)
- [Send Hardest Problems My Way: Probabilistic Path Prioritization for Hybrid Fuzzing, 2019](https://www.cs.ucr.edu/~heng/pubs/digfuzz_ndss19.pdf)
- [Life after Speech Recognition: Fuzzing Semantic Misinterpretation for Voice Assistant Applications, 2019](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_08-4_Zhang_paper.pdf)
- [INSTRIM: Lightweight Instrumentation for Coverage-guided Fuzzing, 2018](https://www.ndss-symposium.org/wp-content/uploads/2018/07/bar2018_14_Hsu_paper.pdf)
- [IoTFuzzer: Discovering Memory Corruptions in IoT Through App-based Fuzzing, 2018](http://wp.internetsociety.org/ndss/wp-content/uploads/sites/25/2018/02/ndss2018_01A-1_Chen_paper.pdf)
- [What You Corrupt Is Not What You Crash: Challenges in Fuzzing Embedded Devices, 2018](http://s3.eurecom.fr/docs/ndss18_muench.pdf)
- [Enhancing Memory Error Detection for Large-Scale Applications and Fuzz Testing, 2018](https://lifeasageek.github.io/papers/han:meds.pdf)
- [Vuzzer: Application-aware evolutionary fuzzing, 2017](https://www.ndss-symposium.org/ndss2017/ndss-2017-programme/vuzzer-application-aware-evolutionary-fuzzing/)
- [DELTA: A Security Assessment Framework for Software-Defined Networks, 2017](https://www.ndss-symposium.org/wp-content/uploads/2017/09/ndss201702A-1LeePaper.pdf)
- [Driller: Augmenting Fuzzing Through Selective Symbolic Execution, 2016](https://cancer.shtech.org/wiki/uploads/2016---NDSS---driller-augmenting-fuzzing-through-selective-symbolic-execution.pdf)
- [Automated Whitebox Fuzz Testing, 2008](https://www.ndss-symposium.org/wp-content/uploads/2017/09/Automated-Whitebox-Fuzz-Testing-paper-Patrice-Godefroid.pdf)
- [Fuzzing JavaScript Engines with Aspect-preserving Mutation, 2020](https://jakkdu.github.io/pubs/2020/park:die.pdf)
- [IJON: Exploring Deep State Spaces via Fuzzing, 2020](https://www.syssec.ruhr-uni-bochum.de/media/emma/veroeffentlichungen/2020/02/27/IJON-Oakland20.pdf)
- [Krace: Data Race Fuzzing for Kernel File Systems, 2020](https://www.cc.gatech.edu/~mxu80/pubs/xu:krace.pdf)
- [Pangolin:Incremental Hybrid Fuzzing with Polyhedral Path Abstraction, 2020](https://qingkaishi.github.io/public_pdfs/SP2020.pdf)
- [RetroWrite: Statically Instrumenting COTS Binaries for Fuzzing and Sanitization, 2020](https://www.semanticscholar.org/paper/RetroWrite%3A-Statically-Instrumenting-COTS-Binaries-Dinesh-Burow/845cafb153b0e4b9943c6d9b6a7e42c14845a0d6)
- [Full-speed Fuzzing: Reducing Fuzzing Overhead through Coverage-guided Tracing, 2019](https://www.computer.org/csdl/proceedings-article/sp/2019/666000b122/19skgbGVFEQ)
- [Fuzzing File Systems via Two-Dimensional Input Space Exploration, 2019](https://www.computer.org/csdl/proceedings-article/sp/2019/666000a594/19skfLYOpaw)
- [NEUZZ: Efficient Fuzzing with Neural Program Smoothing, 2019](https://www.computer.org/csdl/proceedings-article/sp/2019/666000a900/19skg5XghG0)
- [Razzer: Finding Kernel Race Bugs through Fuzzing, 2019](https://www.computer.org/csdl/proceedings-article/sp/2019/666000a296/19skfwZLirm)
- [Angora: Efficient Fuzzing by Principled Search, 2018](http://web.cs.ucdavis.edu/~hchen/paper/chen2018angora.pdf)
- [CollAFL: Path Sensitive Fuzzing, 2018](http://chao.100871.net/papers/oakland18.pdf)
- [T-Fuzz: fuzzing by program transformation, 2018](https://nebelwelt.net/publications/files/18Oakland.pdf)
- [Skyfire: Data-Driven Seed Generation for Fuzzing, 2017](https://www.ieee-security.org/TC/SP2017/papers/42.pdf)
- [Program-Adaptive Mutational Fuzzing, 2015](https://softsec.kaist.ac.kr/~sangkilc/papers/cha-oakland15.pdf)
- [TaintScope: A checksum-aware directed fuzzing tool for automatic software vulnerability detection, 2010](https://ieeexplore.ieee.org/abstract/document/5504701)
- [FANS: Fuzzing Android Native System Services via Automated Interface Analysis, 2020](https://www.usenix.org/conference/usenixsecurity20/presentation/liu)
- [Analysis of DTLS Implementations Using Protocol State Fuzzing, 2020](https://www.usenix.org/conference/usenixsecurity20/presentation/fiterau-brostean)
- [EcoFuzz: Adaptive Energy-Saving Greybox Fuzzing as a Variant of the Adversarial Multi-Armed Bandit, 2020](https://www.usenix.org/conference/usenixsecurity20/presentation/yue)
- [Fuzzing Error Handling Code using Context-Sensitive Software Fault Injection, 2020](https://www.usenix.org/conference/usenixsecurity20/presentation/jiang)
- [FuzzGen: Automatic Fuzzer Generation, 2020](https://www.usenix.org/conference/usenixsecurity20/presentation/ispoglou)
- [ParmeSan: Sanitizer-guided Greybox Fuzzing, 2020](https://www.usenix.org/conference/usenixsecurity20/presentation/osterlund)
- [SpecFuzz: Bringing Spectre-type vulnerabilities to the surface, 2020](https://www.usenix.org/conference/usenixsecurity20/presentation/oleksenko)
- [FuzzGuard: Filtering out Unreachable Inputs in Directed Grey-box Fuzzing through Deep Learning, 2020](https://www.usenix.org/conference/usenixsecurity20/presentation/zong)
- [Montage: A Neural Network Language Model-Guided JavaScript Engine Fuzzer, 2020](https://www.usenix.org/conference/usenixsecurity20/presentation/lee-suyoung)
- [GREYONE: Data Flow Sensitive Fuzzing, 2020](https://www.usenix.org/conference/usenixsecurity20/presentation/gan)
- [Fuzzification: Anti-Fuzzing Techniques, 2019](https://www.usenix.org/conference/usenixsecurity19/presentation/jung)
- [AntiFuzz: Impeding Fuzzing Audits of Binary Executables, 2019](https://www.usenix.org/conference/usenixsecurity19/presentation/guler)
- [Charm: Facilitating Dynamic Analysis of Device Drivers of Mobile Systems, 2018](https://www.usenix.org/conference/usenixsecurity18/presentation/talebi)
- [MoonShine: Optimizing OS Fuzzer Seed Selection with Trace Distillation, 2018](https://www.usenix.org/conference/usenixsecurity18/presentation/pailoor)
- [QSYM : A Practical Concolic Execution Engine Tailored for Hybrid Fuzzing, 2018](https://www.usenix.org/conference/usenixsecurity18/presentation/yun)
- [OSS-Fuzz - Google's continuous fuzzing service for open source software, 2017](https://www.usenix.org/conference/usenixsecurity17/technical-sessions/presentation/serebryany)
- [kAFL: Hardware-Assisted Feedback Fuzzing for OS Kernels, 2017](https://www.usenix.org/conference/usenixsecurity17/technical-sessions/presentation/schumilo)
- [Protocol State Fuzzing of TLS Implementations, 2015](https://www.usenix.org/conference/usenixsecurity15/technical-sessions/presentation/de-ruiter)
- [Optimizing Seed Selection for Fuzzing, 2014](https://softsec.kaist.ac.kr/~sangkilc/papers/rebert-usenixsec14.pdf)
- [Dowsing for overflows: a guided fuzzer to find buffer boundary violations, 2013](http://enigma.usenix.org/sites/default/files/sec13_proceedings_interior.pdf#page=57)
- [Fuzzing with Code Fragments, 2012](https://www.usenix.org/system/files/conference/usenixsecurity12/sec12-final73.pdf)
- [Intriguer: Field-Level Constraint Solving for Hybrid Fuzzing, 2019](https://dl.acm.org/citation.cfm?id=3354249)
- [Learning to Fuzz from Symbolic Execution with Application to Smart Contracts, 2019](https://files.sri.inf.ethz.ch/website/papers/ccs19-ilf.pdf)
- [Matryoshka: fuzzing deeply nested branches, 2019](https://web.cs.ucdavis.edu/~hchen/paper/chen2019matryoshka.pdf)
- [Evaluating Fuzz Testing, 2018](http://www.cs.umd.edu/~mwh/papers/fuzzeval.pdf)
- [Hawkeye: Towards a Desired Directed Grey-box Fuzzer, 2018](https://chenbihuan.github.io/paper/ccs18-chen-hawkeye.pdf)
- [IMF: Inferred Model-based Fuzzer, 2017](http://daramg.gift/paper/han-ccs2017.pdf)
- [SemFuzz: Semantics-based Automatic Generation of Proof-of-Concept Exploits, 2017](https://www.informatics.indiana.edu/xw7/papers/p2139-you.pdf)
- [AFL-based Fuzzing for Java with Kelinci, 2017](https://dl.acm.org/citation.cfm?id=3138820)
- [Designing New Operating Primitives to Improve Fuzzing Performance, 2017](http://iisp.gatech.edu/sites/default/files/images/designing_new_operating_primitives_to_improve_fuzzing_performance_vt.pdf)
- [Directed Greybox Fuzzing, 2017](https://dl.acm.org/citation.cfm?id=3134020)
- [SlowFuzz: Automated Domain-Independent Detection of Algorithmic Complexity Vulnerabilities, 2017](https://arxiv.org/pdf/1708.08437.pdf)
- [DIFUZE: Interface Aware Fuzzing for Kernel Drivers, 2017](https://acmccs.github.io/papers/p2123-corinaA.pdf)
- [Systematic Fuzzing and Testing of TLS Libraries, 2016](https://www.nds.rub.de/media/nds/veroeffentlichungen/2016/10/19/tls-attacker-ccs16.pdf)
- [Coverage-based Greybox Fuzzing as Markov Chain, 2016](https://ieeexplore.ieee.org/abstract/document/8233151)
- [eFuzz: A Fuzzer for DLMS/COSEM Electricity Meters, 2016](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.817.5616&rep=rep1&type=pdf)
- [Scheduling Black-box Mutational Fuzzing, 2013](https://softsec.kaist.ac.kr/~sangkilc/papers/woo-ccs13.pdf)
- [Taming compiler fuzzers, 2013](https://www.cs.utah.edu/~regehr/papers/pldi13.pdf)
- [SAGE: whitebox fuzzing for security testing, 2012](https://dl.acm.org/citation.cfm?id=2094081)
- [Grammar-based whitebox fuzzing, 2008](https://dl.acm.org/citation.cfm?id=1375607)
- [Taint-based directed whitebox fuzzing, 2009](https://dl.acm.org/citation.cfm?id=1555061)


## Malware
- [An Abstract Theory of Computer Viruses](https://www.cin.ufpe.br/~ruy/crypto/virus/ala01.pdf)
- [System-level support for intrusion recovery](http://www.syssec-project.eu/m/page-media/3/diskduster-dimva12.pdf)
- [Automated classification and analysis of internet malware](https://jon.oberheide.org/files/raid07-malware.pdf)
- [WYSINWYX: What You See Is Not What You eXecute](https://research.cs.wisc.edu/wpis/papers/wysinwyx.final.pdf)
- [Quincy: Detecting Host-Based Code Injection Attacks in Memory Dumps](https://net.cs.uni-bonn.de/fileadmin/ag/martini/Staff/barabosch_quincy_dimva2017.pdf)
- [Bee master: Detecting host-based code injection attacks](https://net.cs.uni-bonn.de/fileadmin/ag/martini/Staff/barabosch_bee_master_dimva_2014.pdf)
- [Host-based code injection attacks: A popular technique used by malware](https://net.cs.uni-bonn.de/fileadmin/ag/martini/Staff/barabosch_HBCIAs_MALCON_2014.pdf)
- [Scalable, Behavior-Based Malware Clustering](https://sites.cs.ucsb.edu/~chris/research/doc/ndss09_cluster.pdf)
- [A View on Current Malware Behaviors](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.448.3918&rep=rep1&type=pdf)
- [Dynamic analysis of malicious code](https://sites.cs.ucsb.edu/~chris/research/doc/virology06_dynamic.pdf)
- [Behavior abstraction in malware analysis.](https://hal.inria.fr/inria-00536500/file/RV-preprint.pdf)
- [Detecting Hardware-Assisted Virtualization](https://christian-rossow.de/publications/detectvt-dimva2016.pdf)
- [BitScope: Automatically Dissecting Malicious Binaries](http://bitblaze.cs.berkeley.edu/papers/bitscope_tr_2007.pdf)
- [On the Limits of Information Flow Techniques for Malware Analysis and Containment](https://www.comp.nus.edu.sg/~prateeks/papers/saxena-dimva08.pdf)
- [Understanding Linux Malware](https://reyammer.io/publications/2018_oakland_linuxmalware.pdf)
- [Ether: Malware Analysis via Hardware Virtualization Extensions](http://ether.gtisc.gatech.edu/ether_ccs_2008.pdf)
- [Dynamic Spyware Analysis](http://bitblaze.cs.berkeley.edu/papers/usenix07.pdf)
- [A Survey on Automated Dynamic Malware Analysis Techniques and Tools](https://publications.sba-research.org/publications/malware_survey.pdf)
- [CodeXt: Automatic Extraction of Obfuscated Attack Code from Memory Dump](https://cs.gmu.edu/~xwangc/Publications/ISC2014-AttackCodeExtraction-final.pdf)
- [A Survey of Mobile Malware in the Wild](https://www.cs.odu.edu/~cs441/Papers/sec-011.pdf)
- [Attacks on More Virtual Machine Emulators](http://pferrie.tripod.com/papers/attacks2.pdf)

## Binary analysis
- [ByteWeight: Learning to Recognize Functions in Binary Code](https://www.usenix.org/system/files/conference/usenixsecurity14/sec14-paper-bao.pdf)
- [CoDisasm: Medium Scale Concatic Disassembly of Self-Modifying Binaries with Overlapping Instructions](https://hal.inria.fr/hal-01257908/document)
- [Minemu: The World’s Fastest Taint Tracker](http://www.few.vu.nl/~herbertb/papers/minemu_raid11.pdf)
- [When good instructions go bad: Generalizing return-oriented programming to risc.](https://sjmulder.nl/dl/pdf/unsorted/2008%20-%20Bachanan%20et%20al%20-%20When%20Good%20Instructions%20Go%20Bad.pdf)
- [An API for Runtime Code Patching](http://www.cs.umd.edu/~hollings/papers/apijournal.pdf)
- [Reverse Engineering of Binary Device Drivers with RevNIC](https://dslab.epfl.ch/pubs/revnic.pdf)
- [https://apps.dtic.mil/sti/pdfs/AD1034415.pdf](https://apps.dtic.mil/sti/pdfs/AD1034415.pdf)
- [Graph-based comparison of executable objects](https://static.googleusercontent.com/media/www.zynamics.com/en//downloads/bindiffsstic05-1.pdf)
- [TaintDroid: An Information-Flow Tracking System for Realtime Privacy Monitoring on Smartphones](https://static.usenix.org/event/osdi10/tech/full_papers/Enck.pdf)
- [Structural Comparison of Executable Objects](https://static.googleusercontent.com/media/www.zynamics.com/en//downloads/dimva_paper2.pdf)
